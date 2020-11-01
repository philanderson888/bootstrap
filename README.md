# bootstrap

A playground for learning bootstrap

## Contents

- [bootstrap](#bootstrap)
  - [Contents](#contents)
  - [IDE](#ide)
- [Bootstrap Intro](#bootstrap-intro)
- [Navbar Collapsing Menu](#navbar-collapsing-menu)
- [Bootstrap Dropdown](#bootstrap-dropdown)
- [Bootstrap Classes](#bootstrap-classes)


## IDE

[{{ pageSvc.title() }}](https://www.codeply.com/go/qhaBrcWp3v)

# Bootstrap Intro

**Bootstrap** is the most popular HTML, CSS, and JavaScript framework for developing responsive, mobile-first web sites. **Bootstrap** is completely free to download and use!

**Bootstrap** is an open-source Javascript framework. It is a combination of HTML, CSS, and Javascript code designed to help build user interface components. **Bootstrap** was also programmed to support both HTML5 and CSS3. Also it is called Front-end-framework.

Important Links

[http://www.w3schools.com/bootstrap/](http://www.w3schools.com/bootstrap/)

[http://getbootstrap.com/](http://getbootstrap.com/)

[http://startbootstrap.com/](http://startbootstrap.com/)

[http://pikock.github.io/bootstrap-magic/](http://pikock.github.io/bootstrap-magic/)

LESS Leaner CSS

[http://lesscss.org](http://lesscss.org/)

Variables.less file

MIXINS allow mixing class names as properties in other classes

Bootstrap 4 update

See [https://www.codeply.com/go/qhaBrcWp3v](https://www.codeply.com/go/qhaBrcWp3v) for a Bootstrap 4 update on NavBar links

# Navbar Collapsing Menu

```jsx
Firstly in the navbar create the button

<div class="navbar navbar-default navbar-fixed-top">
	<div class="container">
		<button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
		</button>
	</div>
</div>

```

# Bootstrap Dropdown

```csharp
<li class="dropdown">
    <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                          Northwind <b class="caret"></b></a>
    <ul class="dropdown-menu">
        <li><a asp-page="/AllCustomers">All Customers</a></li>
        <li><a asp-page="/NorthwindCustomers">Customers</a></li>
        <li><a asp-page="/InjectedCustomers">Injected Customers</a></li>
    </ul>
</li>
```

# Bootstrap Classes

Nested Grid

Responsive Images

GlyphIcons

Carousel

Modal Window

Container : allows us to center text

Container : allows us to set container-max-width at every media query breakpoint

Page-header : puts a margin-top on our block

Nav class turns an unordered list into a great looking list!!!

Bootstrap default grid classess : phone, tablet, desktop, large desktop

Img-responsive to make an image responsive

Col-md-pull-6 or col-md-push-6 pushes or pulls content one way

Nav makes an unordered list look great

Nav-pills makes an unordered list (nav) go horizontal

Pull-right

Nav-tabs makes an unordered list (nav) go horizontal

Visible-xs content is only visible in smaller devices

Navbar just puts a horizontal band across our site

Navbar-default sets the colouring (very light grey) for a navbar

Navbar has a container INSIDE it! So content is same width as below!

Navbar-brand

Text-muted can be used in a navbar-brand

collapse navbar-collapse used in a navbar menu to make it disappear below breakpoint in order to permit a collapsable menu to appear at that breakpoint also

Nav navbar-nav puts an <ul> inside a navbar horizontally

Nav navbar-nav navbar-right pulls all navbar content to the right

Navbar-inverse gives navbar all the dark colours

Navbar-fixed-top fixes the navbar to the top of the screen (have to add a 70 pixel margin-top to the body when you do this or alternatively use page-header class on the first item below the navbar

Navbar-toggle places the drop-down menu to the top right when the screen width breakpoint is reached and the horizontal menu disappears

Container max-width 1000px sets screen to max width

Dropdown in <li> makes it a dropdown menu

<b class="caret"> makes dropdown arrow symbol to indicate a dropdown menu

<ul class="dropdown-menu"> creates a dropdown menu in a navbar

<li class="divider"> in a drop-down menu, provides a divider item

<b class="glyphicon glyphicon-camera"> adds a glyphicon to our page

Carousel : plays photos round and round

<div class="carousel"> creates a carousel

<div class="carousel slide jumbotron"> allows carousel to slide from side to side

<div class="carousel-inner"> creates inèner carousel content

<div class="item active"> is item within carousel-inner div

<div class="modal fade" fades in from the top

<div class="modal-dialog" centers any modal dialog

<div class="modal-content" gives background colour and shape

<div class="modal-header and modal-content"> actual text of modal

<button class="close">

<data-dismiss="modal"> allows the modal window to close on click

Nav-pills

Nav-stacked

Nav-tabs

.show

.hidden

.sr-only screen reader only

.invisible means it still affects screen flow

Clearfix
