mobile-menu
===========

A mobile menu as Finite State Machnine - Moore, to be exact.

DEPENDENCIES:

The menu is comprised of HTML, CSS, and JavaScript.

mobile-menu-flip.html & mobile-menu-flip.css

mobile-menu-slide.hml & mobile-menu-slide.css

Both menus require:

jquery.js & mobile-menu-static.js 
(there also exists a dynamic version in which the menu is populated via AJAX from JSON)


1. The HTML files are the same with the exception of the reference to the appropriate CSS file
2. The transitions, or states, are executed via JavaScript (jQuery).
3. The transitions are defined in the CSS using CSS3 transitions and 3D Transforms to take advantage of hardware acceleration whenever possible.
 
 
SUPPORTED DEVICES: 

Sliding Menu: iPhone 4 + up, Android 2.3.3 + up, Windows 8 phone 

Card Flip Menu: iPhone 

NOTE: Even though Android "supports" 3D transforms, it doesn't do it well. So instead of feature detection, UA detection is used to target Android, and Not use 3D
