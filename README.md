# Ultralight Responsive Grid
Light weight responsive grid css framework. Lightweight filesize makes it download faster. It is based on mobile first or small screen first. Build on sass / scss thus easily configurable. Lightweight css grid has wide variety of features such as classes for push, pull, no gutters, expand, hide, show, hide or show only on specific screen. etc.

* [Project Page](http://www.egrapes.in/projects/css/ultralight-responsive-grid/) - Project Page
* [Getting Started](https://neerajmourya.github.io/ultralight-responsive-grid/) - Getting Started

# Basics
## How to use

To create a row use :

```
<div class="rw"></div>
```

To create columns use :

```
<div class="rw">
  <div class="cl s12 m6 l4">Column 1</div>
  <div class="cl s12 m6 l4">Column 2</div>
  <div class="cl s12 m6 l4">Column 3</div>
</div>
```
Above code will create 1 column layout on small screen, 2 columns layout on medium screens, and 3 columns layout on large screens.

Where,

s1, s2, s3 .................s12 are 12 grid classes can be used for small screens.

m1, m2, m3 .................m12 are 12 grid classes can be used for medium screens.

l1, l2, l3 .................m12 are 12 grid classes can be used for large screens.

To collapse columns padding or collapse gutters within a row use :

```
<div class="rw ngt">
  <div class="col s12 m6 l4">Column 1</div>
  <div class="col s12 m6 l4">Column 2</div>
  <div class="col s12 m6 l4">Column 3</div>
</div>
```

To push columns on small screens use :
spus1, spus2, spus3 .......................spus12

To push columns on medium screens use :
mpus1, mpus2, mpus3 .......................mpus12

To push columns on large screens use :
lpus1, lpus2, lpus3 .......................lpus12


To pull columns on small screens use :
spul1, spul2, spul3 .......................spul12

To pull columns on medium screens use :
mpul1, mpul2, mpul3 .......................mpul12

To pull columns on large screens use :
lpul1, lpul2, lpul3 .......................lpul12
