#Responsive Images

The point: Analyze and provide examples of some standard patterns for handling responsive images across platform.

##Background Images

###The Pattern

.image{
  background-image: url(http://www.placecage.com/200/300);
}

@media (max-width: 600px) {
  .image
    background-image: url(http://www.placecage.com/600/600);
  }
}

###Example

[#](INSERT LINK HERE)

###The Benefit

* Allows the user to only download the necessary image for their screen size.
* Easy to implement.

###The Issues

* Does not take into account Network Speed
  *A user on laptop using a mobile hotspot will still have to sownload the full size image(not ideal).

* Uses to CSS to manage content.
  *This goes against the seperation of markup and styling.


###Resources
[http://mobile.smashingmagazine.com/2013/07/22/simple-responsive-images-with-css-backgrounds/](http://mobile.smashingmagazine.com/2013/07/22/simple-responsive-images-with-css-backgrounds/)

[http://css-tricks.com/snippets/css/retina-display-media-query/](http://css-tricks.com/snippets/css/retina-display-media-query/)


##SVG

###Resources
http://demosthenes.info/blog/744/

###The Benefit:
* Scales responsively with only one image.

###The Issues:
* Not supported by all browsers.

###Resources
[http://demosthenes.info/blog/744/](http://demosthenes.info/blog/744/)
[http://caniuse.com/#feat=svg](http://caniuse.com/#feat=svg)


##Font Icons

###Resources
[http://caniuse.com/#feat=fontface](http://caniuse.com/#feat=fontface)
[http://icomoon.io/](http://icomoon.io/)


##Detecting Network Speed


##New HTML Element


##W3C Picture Element Proposal


##PictureFill


##PhotoShop Plugin for Resizing Images


##Other great resources:

[http://css-tricks.com/which-responsive-images-solution-should-you-use/](http://css-tricks.com/which-responsive-images-solution-should-you-use/)

