Bootstrap 3.2 - Sublime Plugin
==================


A sublime plugin complete with Bootstrap 3 snippets

Feel free to let me know what else you want added via:

- Twitter [@JasonMortonNZ](https://twitter.com/jasonmortonnz)
- [Issues](https://github.com/JasonMortonNZ/bs3-sublime-plugin/issues)


Changes:
===========
- omitted all of (bs3-?) ,except for (CDN ,Templates) "writing bs3- everytime i want to make a div was an agony"
- Updated CDN references to Bootstrap v3.2
- changes are written next to each corespondent section.
- included a fix for @BootStrap awkward "container-fluid + row" (padding,margin) problem ,just add this classes to your css

<pre>
<!-- for container-fluid & columns -->
.no-padding {
	padding-right: 0 !important;
	padding-left: 0 !important;
}

<!-- for row -->
.no-margin {
	margin-right: 0 !important;
	margin-left: 0 !important;
}

<!-- for invidual column control -->
.no-margin-right {
   	margin-right: 0 !important;
}
.no-margin-left {
	margin-left: 0 !important;
}
</pre>

## What's included - contents
- [CDN](#cdn)
- [Templates](#templates)
- [Forms](#forms)
- [Tables](#tables)
- [Input](#input-fields-form-fields)
- [Alerts](#alerts)
- [Badges](#badges)
- [Breadcrumbs](#breadcrumbs)
- [Buttons](#buttons)
- [Carousel](#carousel)
- [Grid](#grid)
- [Images](#images)
- [Icons](#icons)
- [Labels](#labels)
- [Pagination](#pagination)
- [Navigation](#navigation)
- [Panels](#panels)
- [List Groups](#list-groups)
- [Media Objects](#media-objects)
- [Icons](#icons)
- [Clearfix](#clearfix)
- [License](#license)

### CDN

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| CDN link (both CSS & JS)       | bs3-cdn                        |
| CDN link (CSS only)            | bs3-cdn:css                    |
| CDN link (JS only)             | bs3-cdn:js                     |

### Templates

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| HTML5 Template Layout          | bs3-template:html5             |

### Forms (add has-?)

| Component       				 | Snippet code        			  |
|------------------------------- | :-----------------------------:|
| Form            				 | form            			      |
| Inline Form     				 | form:inline     			      |
| Horizontal Form 				 | form:horizontal 			      |

### Tables

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Table                    		 | table                      	  |
| Bordered Table           		 | table:bordered             	  |
| Condensed Table          		 | table:condensed            	  |
| Hover Table              		 | table:hover                	  |
| Striped Table            		 | table:striped              	  |

### Input Fields (Form fields)

**Note:** you can add " :h " to the end of any input field snippet to make it compatible with Bootstrap 3 horizontal forms. **E.g.**
- input:text:h
- input:hidden:h


| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----:	|
| Label		 					 | input:label   			  	  |    		|
| Text Input               		 | input:text 				  	  | :h 		|
| Email Input 					 | input:email   			  	  | :h 		|
| Password Input				 | input:password  			  	  | :h 		|
| Hidden Input					 | input:hidden  			  	  | :h 		|
| Url Input						 | input:url 	 			  	  | :h 		|
| Color Input 					 | input:color   			  	  | :h 		|
| Number Input 					 | input:number   			  	  | :h 		|
| Range Input 					 | input:range   			  	  | :h 		|
| Date Input 					 | input:date   			  	  | :h 		|
| Week Input 					 | input:week   			  	  | :h 		|
| Month Input 					 | input:month   			  	  | :h 		|
| Time Input 					 | input:time   			  	  | :h 		|
| Tel Input 					 | input:tel   	 			  	  | :h 		|
| Search Input 					 | input:search   			  	  | :h 		|
| Reset Input 					 | input:reset   			  	  | :h 		|
| Submit Input 					 | input:submit   			  	  | :h 		|
| Checkbox Input 				 | input:checkbox  			  	  | :h 		|
| Radio Box Input 				 | input:radio  			  	  | :h 		|
| Select Box 	 				 | select		  			  	  | :h 		|

### Alerts

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Alert Box (Default)			 | alert 					  	  |
| Danger Alert Box				 | alert:danger 			  	  |
| Info Alert Box				 | alert:info				  	  |
| Success Alert Box              | alert:success              	  |
| Warning Alert Box				 | alert:warning			  	  |

### Badges

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Badge (Default) 				 | badge 			  			  |

### Breadcrumbs

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Breadcrumbs	 				 | breadcrumbs					  |

### Carousel (the original was overwelming so i add a more simplified version for both "p" + "img")

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Carousel original snippet		 | carousel-orig			  	  |
| Carousel for Image			 | carousel-img   			  	  |
| Carousel for text 			 | carousel	       			  	  |

### Buttons (changed "?-button" > "btn-?" ,changed "large > "lg")

**Note:** all button snippets below can have any of the following options append to the end of the snippet *.
- :danger
- :default
- :disabled
- :info
- :primary
- :success
- :warning

**An example:**
- btn:success
- btn-lg:disabled
- btn-block:warning

| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----:	|
| Button		 				 | btn						 	  |  *		|
| Block Button	 				 | btn-block				 	  |  *		|
| Mini Button		 			 | btn-xs				  	 	  |	 *		|
| Small Button		 			 | btn-sm				  	 	  |	 *		|
| Large Button		 			 | btn-lg				  	 	  |	 *		|
| Button toolbar		 		 | btn-toolbar				  	  |	 *		|
| Button group		 			 | btn-group				  	  |	 *		|

### Grid (omitted the col(:) + add col-xs,sm,md,lg & offset-? + container-fluid)

**Note:** The bs3-col snippet can be used both on its own or with the addition of a colon followed by the number of columns required: **E.g.**

- col
- col6
- col12

| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----:	|
| Column		 				 | col						  	  | 1-12	|
| Large Column		 			 | col-lg						  |			|
| large Column offset		 	 | col-lg-off					  |			|
| Row			 				 | row							  |  		|
| Container		 				 | container					  |			|
| Container-fluid 				 | container-fluid				  |			|

### Icons (removed the extra icon folder + add "fa-?" + now its just (icon:g / icon:f))

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| Glyphicon		                 | icon:g                         |
| Icon (Font Awesome)		     | icon:f                         |

### Images (add imageshapes + changed "image" > "img" , "thumbnail" > "thumb")

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Thumbnail	 					 | thumb 					  	  |
| Thumbnail with content		 | thumb:content			  	  |
| image							 | img						  	  |
| image-shapes					 | imgshape					  	  |

### Labels (add "control-label")

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Label		 					 | label 	 				  	  |
| Danger Label					 | label:danger				  	  |
| Info Label					 | label:info 				  	  |
| Success Label					 | label:success			  	  |
| Warning Label					 | label:warning			  	  |

### Pagination (changed "large" to "lg")

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Pager		 					 | pager	 				      |
| Aligned Pager             	 | pager:aligned 			      |
| Pagination					 | pagination				      |
| Pagination:small				 | pagination:small			      |
| Pagination:large				 | pagination:large			      |

### Navigation

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Navbar (basic navbar)			 | navbar	 				      |
| Navbar Brand Element			 | navbar:brand				      |
| Navbar Button					 | navbar:button			      |
| Navbar Form 					 | navbar:form 				      |
| Navbar Link 					 | navbar:link 				      |
| Navbar Text 					 | navbar:text 				      |
| Navbar Fixed-Botton			 | navbar:fixed-bottom		      |
| Navbar Fixed-Top				 | navbar:fixed-top			      |
| Navbar Inverse				 | navbar:inverse			      |
| Navbar Responsive				 | navbar:responsive		      |
| Navbar Static-Top				 | navbar:static-top		      |

### Jumbotron (now its just "jumbo")

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Jumbotron (ex Hero Unit)		 | jumbo     				  |

### Panels

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Panel                          | panel                          |
| Panel (contextual)             | panel:{warning,success,info,danger,primary}                  |
| Panel (with heading)           | panel:heading                  |
| Panel (with footer)            | panel:footer                   |

### List-groups

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| List group                     | list-group                 	  |
| List group (with badges)       | list-group:badges          	  |
| List group (linked list)       | list-group:linked          	  |
| List group (with content)      | list-group:content         	  |

### Media Objects (its now only media)

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Media Object                   | media                          |

### Clearfix

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Clearfix                       | clearfix                       |

### License

Bootstrap 3 - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).



