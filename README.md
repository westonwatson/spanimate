#Spanimate.css
*Pure CSS animation*

##Usage
To use spanimate.css in your website, simply drop the stylesheet into your document's `<head>`, and add the class `spanimate` to an element, along with any of the animation names. That's it! You've got a CSS animated element. Sweet!

You can do a whole bunch of other stuff with spanimate.css when you combine it with jQuery or add your own CSS rules. Dynamically add animations using jQuery with ease:

```javascript
$('#yourElement').addClass('spanimate bounceOutLeft');
```

You can change the duration of your animations, add a delay or change the number of times that it plays!

```css
#yourElement {
	-vendor-animation-duration: 3s;
	-vendor-animation-delay: 2s;
	-vendor-animation-iteration-count: infinite;
}
```
##Cheat Sheet

####Attention seekers:
flash
bounce
shake
tada
swing
wobble
wiggle
pulse

####Flippers (currently Webkit, Firefox, &amp; IE10 only):
flip
flipInX
flipOutX
flipInY
flipOutY

####Fading entrances:
fadeIn
fadeInUp
fadeInDown
fadeInLeft
fadeInRight
fadeInUpBig
fadeInDownBig
fadeInLeftBig
fadeInRightBig

####Fading exits:
fadeOut
fadeOutUp
fadeOutDown
fadeOutLeft
fadeOutRight
fadeOutUpBig
fadeOutDownBig
fadeOutLeftBig
fadeOutRightBig

####Bouncing entrances:
bounceIn
bounceInDown
bounceInUp
bounceInLeft
bounceInRight

####Bouncing exits:
bounceOut
bounceOutDown
bounceOutUp
bounceOutLeft
bounceOutRight

####Rotating entrances:
rotateIn
rotateInDownLeft
rotateInDownRight
rotateInUpLeft
rotateInUpRight

####Rotating exits:
rotateOut
rotateOutDownLeft
rotateOutDownRight
rotateOutUpLeft
rotateOutUpRight

####Lightspeed:
lightSpeedIn
lightSpeedOut

####Specials:
hinge
rollIn
rollOut