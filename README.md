TOSS THOSE WAVES

This repo will help reinforce what we learned about keyframes
and positioning.  You will be cloning this project.

https://spencerkekauoha.github.io/lesson-waves-keyframes/

////////////////////////////////////

STEP: 1

Fork this repo to get all the project files  
NOTE (Don't look at the code yet!  Only use it if you get stuck!)
https://github.com/SpencerKekauoha/lesson-waves-keyframes

In a seperate folder:
Create an Index.html and Styles.css

Don't forget to include your viewport meta tag and your reset and/or normalize files.

////////////////////////////////////

STEP: 2

Before we attempt to animate anything, position your the images so they appear to be
one image.

It should look like this when it is positioned:
http://greatwavekanagawa.com/Great%20Wave%20Hokusai.jpg

* HINT
Due to the cropping of the images, give the backwave (top: 30px)
Otherwise, if we start at top: 0px, when we animate the images the cropping will be visible
and it won't look good.


After the images are positioned, position the title in the middle of the page.

////////////////////////////////////

STEP: 3

To animate using keyframes, we will only animate backwave and frontwave.  (background will stay motionless)

Give both the backwave and frontwave an attribute of animation.
name your animations different, set a specified animation duration, and how long you want to animate for.

<!-- animation: wavey-back 5s infinite; -->


////////////////////////////////////

STEP: 4

Once the animations are named and given time values, let's
add our keyframes.

swap out nameofanimation with the name of your animation.

<!-- @keyframes nameofanimation {
  animate here
} -->

Have the frontwave start by animating up, then down, then up again
and backwave will start by animating down, then up, then down again.
Having them start in different directions will add to the effect
of our animation.

Tinker with the values until you are satisfied with the result.
