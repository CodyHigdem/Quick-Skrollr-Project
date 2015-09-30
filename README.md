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