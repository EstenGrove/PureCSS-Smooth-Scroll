# PureCSS-Smooth-Scroll
A pure CSS smooth scroll solution using hrefs and ids as targets. 


![smoothscroll](https://user-images.githubusercontent.com/41505038/51793251-ac2f0480-217a-11e9-8b41-1f9dfc2b733e.gif)


Simple Setup:

- First create anchor tags and define "href" that point to the destinations for each scroll.(Preferably keep the different scroll points a fair distance away from each other, to help emphasize the effect)
- Then create the "destinations" and define their "ids". 
- Now when you click on the anchor tag that says "Go to bottom" it will jump to the bottom of the page. However, there's one problem: there's no smooth-scroll. It's just jumping straight to the section of the web page. 
- To enable smooth-scroll, simply set the CSS for your html to have a property called "scroll-behavior: smooth;"
  - html { scroll-behavior: smooth; }
 
 #### Now you have Pure CSS Smooth Scrolling!
