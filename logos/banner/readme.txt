Slider/Description banner for DAoC Portal Launcher
Rev 2

/***********

Changelogs:

1.1
-Updated logotype to be more rich and bold
-Added new server names to list
-Created new heraldy material
-Finalized 3 images for re-release.

1.0 - Release
-Height:150px ;;; Width:568px
-Optimized height and width to correct values

**********/


***DO NOT DELETE THE CODE FROM THE OLD BANNER and DESCRIPTION IT IS CURRENTLY USING PARTS FROM THERE.***

code_for_slider_portal.html
-contains code for slider
-modify this file to add images

-----------------------------------
Example:

<div id="slider">
   <ul>
   <li><a href="http://dolserver.net"><img src="images/banner1.jpg" width="568" height="150" border="0" /></a></li>
   <li><img src="images/banner2.jpg" width="568" height="150" border="0" /></li>
   <li><img src="images/banner3.jpg" width="568" height="150" border="0" /></li>
   </ul>
</div>


Excerpts from code above
<li><a href="http://dolserver.net"><img src="images/banner1.jpg" width="568" height="150" border="0" /></a></li>
-contains links if you would like.  

<a href="dolserver.net"> </a>
-is link

<img src="images/banner1.jpg" width="568" height="150" border="0" />
-source of image keep width and height the same for all

To add another banner lets say you want 4 banners rotating they follow the order.
    <li><img src="images/banner3.jpg" width="568" height="150" border="0" /></li>

<div id="slider">
   <ul>
   <li><a href="http://dolserver.net"><img src="images/banner1.jpg" width="568" height="150" border="0" /></a></li>
   <li><img src="images/banner2.jpg" width="568" height="150" border="0" /></li>
   <li><img src="images/banner3.jpg" width="568" height="150" border="0" /></li>
<!-- Insert Here -->
   <li><img src="images/banner4.jpg" width="568" height="150" border="0" /></li>
<!-- End Insert Here -->
   </ul>
</div>







-----------------------------------

images /
-contains starter images and psd source with additional resources

js /
-contains brains and controls and speed for slider speed and settings

style.css
-contains design code for portal launcher description