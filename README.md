# boostspacer


Integrate Bootspacer with <a href="http://getbootstrap.com/">Bootstrap</a> to develop responsive pages faster.

Manage space between the elements of your page.
Control padding and margin for each breakpoint, scaling automatically:


`<section class="air">`
`<div class="container">`
`<div class="row">`
`<div class="col-lg-12">`
`<div class="space-50-top"><h1>Hey there!</h1></div>`
`...`



LG Breakpoint

.air -> 100px padding top and bottom 
.space -> 100px margin top and bottom 

MD Breakpoint

.air -> 70px padding top and bottom 
.space -> 70px margin top and bottom 

SM Breakpoint

.air -> 50px padding top and bottom 
.space -> 50px margin top and bottom 

XS Breakpoint

.air -> 30px padding top and bottom 
.space -> 30px margin top and bottom

Combine air class with px sizes and positions

Sizes available 30 - 50 - 70 100(Default value) 

Example:

.air-50-top -> padding-top:50px;

.space-30-bottom -> margin-bottom:30px;


If you need 50px padding only for SM

 .air-mobile-sm-50




