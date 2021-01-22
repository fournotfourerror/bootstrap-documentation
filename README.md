# Bootstrap
_Bootstrap is freely available for every. The main features of bootstrap is, it is very simple and easy to use, hug JavaScript plugins are available, easily design mobile friendly website._

* Easy to use
	* _Anybody with just basic knowledge of HTML and CSS can start using Bootstrap_

* Responsive features
	* _Bootstrap's responsive CSS adjusts to phones, tablets, and desktops_

* Mobile-Friendly
	* _Mobile-first approach: In Bootstrap 3, mobile-first styles are part of the core framework_

* Simple Integration
	* _Bootstrap can be simply integrated along with distinct other platforms and frameworks, on existing sites and new ones too and one more things you can also utilize particular elements of Bootstrap along with your current CSS._

* Pre-styled Components
	* _Bootstrap approaches with pre-styled components for alerts, dropdowns, nav bars, etc._

* Customizable Bootstrap
	* _The Bootstrap can be customized as per the designs of your project._

* Browser compatibility
	* _Bootstrap is compatible with all modern browsers (Chrome, Firefox, Internet Explorer, Safari, and Opera)_

* Great grid system
	* _Bootstrap is built on responsive 12-column grids, layouts and components. Whether you need a fixed grid or a responsive, it's only a matter of a few changes._

* Extensive list of components
	* _Whether you need drop down menus, pagination or alert boxes, Bootstrap has got your covered. Some of the components pre styled are; Dropdowns, Button Groups, Navigation Bar, Breadcrumbs, Labels & Badges, Alerts, Progress Bar, And many others._

* Base styling for most HTML elements
	* _A website has many different elements such as headings, lists, tables, buttons, forms, etc. The HTML elements for which styles are provided are; Typography Code, Tables, Forms, Buttons, Images, Icons_

* Good documentation
	* _Not only does Bootstrap offer styling for almost every element a typical website or web application requires, it also provides a great documentation with examples and demo that only make it more easier for even someone new._

### Color codes
* `primary`   => Blue color
* `secondary` => Grey color (Light black color)
* `info`      => Sky blue color
* `danger`    => Red color
* `success`   => Green color
* `warning`   => Orange color
* `dark`      => Black color
* `white`     => White color

Example (Background color)
```html
    <h2 class="bg-primary"> Blue colored background for the text </h2>
```
Example (Text color)
```html
    <h2 class="text-primary"> Blue colored text </h2>
```

### Grid system

_The Bootstrap Grid System is used for layout, specifically Responsive Layouts. ... The Grid is made up of groupings of Rows & Columns inside 1 or more Containers. The Bootstrap Grid can be used alone, without the Bootstrap JavaScript and other CSS Components. You just need to download and reference the “ bootstrap-grid._

For implementing bootstrap grid system, we have to use following classes

* `row` ( _For representing Rows_ )
* `col` ( _For representing Columns_ )

Example
```html
    <div class="row">
		  <div class="col">
			  row-1 col-1
		  </div>

		  <div class="col">
			  row-1 col-2
		   </div>

		  <div class="col">
			  row-1 col-3
		  </div>
	  </div>
```

* Bootstrap grid system is calculated with 12 columns each and every column is having 1 grid of width.

```html
	<div class="row">
		<div class="col-1"> </div>
        </div>
```

We can change the width of each and every grid by mentioning the width. `col-2` is for representing column width with 2 grids.

```html
	<div class="row">
   		<div class="col">
      			1 of 3
    		</div>
    		<div class="col-6">
      			2 of 3 (wider)
    		</div>
    		<div class="col">
      			3 of 3
    		</div>
  	</div>

  	<div class="row">
    		<div class="col">
      			1 of 3
    		</div>
    		<div class="col-5">
      			2 of 3 (wider)
    		</div>
    		<div class="col">
      			3 of 3
    		</div>
  	</div>
```

Use col-{breakpoint}-auto classes to size columns based on the natural width of their content.

```html
	<div class="row justify-content-md-center">
    		<div class="col col-lg-2">
      			1 of 3
   		</div>
    		<div class="col-md-auto">
      			Variable width content
    		</div>
    		<div class="col col-lg-2">
      			3 of 3
    		</div>
  	</div>
  	<div class="row">
    		<div class="col">
      			1 of 3
    		</div>
    		<div class="col-md-auto">
      			Variable width content
    		</div>
    		<div class="col col-lg-2">
      			3 of 3
    		</div>
  	</div>
```

### Responsive Grid system (_Break points_)

By using breakpoints, we can make the grid system as responsive, we can access the grid system in various screen resolutions. We have different classes for different screen resolutions.

* `.col`    => Extra small scale device
* `.col-sm` => Small scale devices (>=576px)
* `.col-md` => Medium scale devices (>=768px)
* `.col-lg` => Large scale devices (>=992px)
* `.col-xl` => eXtra Large Scale devices (>=1200px)

Example

```html
	<!-- Row 1 -->
	<div class="row justify-content-center">
		<div class="col-md-6 col-sm-12- col-lg-4 "> 
			Row-1 Col-1 
		</div>
		
		<div class="col-md-6 col-sm-12- col-lg-4 "> 
			Row-1 Col-1 
		</div>
	</div>
	
	<!-- Row 2 -->
	<div class="row justify-content-center">
		<div class="col-md-6 col-sm-12- col-lg-4 "> 
			Row-2 Col-1 
		</div>
		
		<div class="col-md-6 col-sm-12- col-lg-4 "> 
			Row-2 Col-1 
		</div>
	</div>
```

From the above example, we used two rows, each and every row is having two columns in it. We used various class names for providing responsiveness for every column. `col-md` is for medium scale devices (Smart phones), `col-sm` is for small-scale devices (Old moto e series mobiles), `col-lg` is for large-scale devices (Desktops)

### Tables

We can style the HTML tables by using bootstrap predefined classes. The following are the availables classes for styling tables.

*  `.table`
*  `.table-dark`
	* We can provide dark background for table and table-row.

```html
	<tr class="table-dark">
      		<th scope="row">Dark</th>
      		<td>Cell</td>
      		<td>Cell</td>
    	</tr>
```
*  `.table-bordered` 
	* _Add **.table-bordered** for borders on all sides of the table and cells._

```html
	<table class="table table-bordered"></table>
```

*  `.table-borderless`
	* _Add **.table-borderless** for generating borderless table._

*  `.thead-dark`
*  `.thead-light`
*  `.table-active`
	* _Highlight a table row or cell by adding a .table-active class._

```html
	<table class="table">
  		<thead>
    			<tr>
      				<th scope="col">#</th>
      				<th scope="col">First Name</th>
      				<th scope="col">Last Name</th>
      				<th scope="col">Role</th>
    			</tr>
  		</thead>
		
  		<tbody>
    			<tr class="table-active">
      				<th scope="row">1</th>
      				<td>Hanuman</td>
      				<td>Kumar</td>
      				<td>Multi-skill Trainer</td>
    			</tr>
    			<tr>
      				<th scope="row">2</th>
      				<td>Rajesh</td>
      				<td>Nalleboina</td>
      				<td>Multi-skill Trainer</td>
    			</tr>
   			 <tr>
      				<th scope="row">3</th>
      				<td colspan="2" class="table-active">Swamy kankipati</td>
      				<td>Multi-skill Trainer</td>
    			</tr>
  		</tbody>
	</table>

```

*  `.table-striped`
	* _Use **.table-striped** to add zebra-striping to any table row within the `<tbody>`._

```html
	<table class="table table-striped"></table>
```

*  `.table-hover`
	* _We can observe the background color of each and every row when we are goind to hover it._
	
```html
	<table class="table table-striped table-hover"></table>
```

* Add `.table-sm` to make any .table more compact by cutting all cell padding in half.

```html
	<table class="table table-sm"></table>
```
* Border styles, active styles, and table variants are not inherited by nested tables.
	* _To prevent any styles from leaking to nested tables, we use the child combinator (>) selector in our CSS. Since we need to target all the tds and ths in the thead, tbody, and tfoot, our selector would look pretty long without it. As such, we use the rather odd looking .table > :not(caption) > * > * selector to target all tds and ths of the .table, but none of any potential nested tables._

	* _Note that if you add <tr>s as direct children of a table, those <tr> will be wrapped in a <tbody> by default, thus making our selectors work as intended._

```html
	<table class="table table-striped">
  		<thead></thead>
  		<tbody>
    			<tr>
      				<td colspan="4">
        				<table class="table mb-0"></table>
      				</td>
    			</tr>
  		</tbody>
	</table>
```


#### Attributes for table
*   `colspan`
*   `rowspan`
*   `scope="col|group|colgroup|rowgroup"`
#### Table-responsive-{breakpoint}
*   `.table-responsive`
*   `.table-responsive-sm`
*   `.table-responsive-md`
*   `.table-responsive-lg`

Example:
```html
	<!DOCTYPE html>
<html>
<head>
	<title>:: Bootstrap Tables ::</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<meta name="viewport" content="width=device-width,initial-scale=1">
</head>
<body>
	<div class="container mt-5">
		<div class="table-responsive-md">
			<table class="table  table-bordered  ">
	<thead class="thead-dark">
		<tr class="bg-primary">
			<th scope="col">S.No</th>
			<th>Continent</th>
			<th>First_Name</th>
			<th>Last_Name</th>
			<th>Age</th>
			<th colspan="2">Actions</th>
			
		</tr>
	</thead>
	<tbody>
		<tr>
			<td scope="row">1</td>
			<td rowspan="2">Non Asia</td>
			<td>Warren</td>
			<td>Buffet</td>
			<td>69</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
		<tr>
			<td>2</td>
			<td>Jeff</td>
			<td>Bezzos</td>
			<td>65</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
		<tr >
			<td>3</td>
			<td>Asia</td>
			<td >Mukesh</td>
			<td>Ambani</td>
			<td>60</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
	</tbody>
	
    </table>
		</div>
</div>

</body>
</html>
```
### Cards

*  `.card`
*  `.card-header`
*  `.card-body`
*  `.card-footer`
*  `.card-img-top`
*  `.card-title`
*  `.card-subtitle`
*  `.card-text`
*  `.card-link`
*  `.card-group`
*  `.card-deck`

Example:
```html
	<!DOCTYPE html>
<html>
<head>
	<title>:: Profile card ::</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<meta name="viewport" content="width=device-width,initial-scale=1">
</head>
<body>
<div class="container mt-5">
	<div class="card-deck">
	<div class="card" style="width:18rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>

	</div>
</div>
</body>
</html>

```

