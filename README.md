# Quick-Skrollr-Project
Trying to figure out how to use skrollr fairly quickly.

##Performance

Try to animate only absolute or fixed positioned elements

###Ideal Properties
should work in most of the browsers
translate3d
scale
rotation
opacity


## Data Attributes

    data-bottom-top=""
   	data-top-bottom=""

   	Read this as data top of the element is at the bottom.

   	Then bottom of the element is at the top of the view point.

   	So

   	****
   	*  *
   	****
   	==== // When the top of this new element is at the bottom of the view point. data-bottom-top
   	=  =
   	==== // When the bottom of this element is at the top of the view point. data-top-bottom


make sure to declare units 0% 20% so on and they must always match all key frame units.

## Absolute vs Relative

Absolute is handy when elements are in the header or footer. Elements at the start or end of the page. When you know how long the page is exactly. 3,000 px and then you can animate number of px's because it will never get larger.

An element is showing progress, like a progress bar. This makes the most sense for absolute.

you can target the element when it enters, leaves the view port or when it is in the center. The relative mode can be very powerful then because you can fade things out right before they leave the view port. You make make content vissible when it's in the center. 