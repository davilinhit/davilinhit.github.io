---
layout: travels
title: Simple Timer Circuit  
subcat: hardware
image: /img/thumbs/555timer.png
year: 2013
description: The animating was more complicated than the wiring. 
location: Oregon
---

Just screwing around with circuits.

I recently bought a house and set up a little home office. In the process, I found a bunch of through-hole components that I got from parts unknown and ended up sorting and messing around with them. All of this high-level ChibiOS stuff has been stressing me out so I did something I haven't done in maybe forever -- made a bunch of little circuits for the hell of it.

(Parts Unknown would be an awesome name for an electronics component business.)

 <img src="/img/blinky/IMG_0187.png">

The first question I asked was hey, does this potentiometer work? Do these LEDs? It's a three-pin pot powered off a 9V with output voltage over the LED.

 <img src="/img/blinky/IMG_0194a.png">

I wanted some sort of switch to turn off all power without having to keep unsnapping the 9V header but all I could come up with in my box of parts was a 8-pin switch.

I went through all my through-hole ICs and found that I've accumulated all the usual: logic gates, comparators, muxes, op amps... and 555 timers, which I know of but have never actually used. 

I used a schematic from Forrest Mims' 555 Timer cookbook and wired it up. Then I looked into how to make a gif to post here so it's clear the light is blinking. I figured ffmpeg would work but it's got a note that this feature is deprecated and to use avconv instead. I tried with ffmpeg anyway and got a 141 MB file. 

I went looking for better instructions and found <a href="https://scottlinux.com/2011/07/31/create-animated-gif-in-linux-from-command-line/">Scott's Linux blog</a>.

I made the video with an iPhone 4S and used avconv to grab a photo every second. That gave me four still images to put into the gif. 

<code>avconv -i IMG_0196.MOV -vsync 1 -r 1 -an -y 'frame%d.jpg'</code>

Then I used Scott's instructions to make what turned out to be a pretty crappy gif, through no fault of his. I didn't realize that having fewer frames in an animation means you really have to hold the camera very still, which I didn't. 

<code>mogrify -resize 640x480 *.jpg</code>

<code>convert -delay 20 -loop 0 *.jpg 555blink.gif</code>

 <img src="/img/blinky/555blink1.gif">

Lesson learned: I need a camera tripod and also to automate this process. I looked around and found another movie that was much longer, so I repeated the process and took the first eight frames.
 
 <img src="/img/blinky/555blink2.gif">

<code> mogrify -resize 640x480 *.jpg

convert -delay 30 -loop 0 *.jpg 555blink1.gif

avconv -i IMG_0196.MOV -vsync 1 -r 2 -an -y 'frame%d.jpg'</code>

I should probably have taken twice as many frames per second in the avconv process because it doesn't show that the light should be on the same amount of time each blink. So I did that on the longer movie and ended up selecting the first 10 frames in the sequence, which includes two cycles of the blinking LED.

 <img src="/img/blinky/555blink3.gif">

I kept going for the hell of it, since I had 8 switches to work with. I added a little push-button switch to turn on the LED on the button press. Having both hooked up at the same time meant the LED up top was blinking as per the 555 timer but pressing the button down below sunk all current through the bottom LED.

 <img src="/img/blinky/IMG_0199.png">

It seems like it'd be pretty easy to fake a GIF, to do sleight of hand, and to demonstrate performance or meeting a spec that isn't actually there. This last gif is the longest, the largest, with 2fps to pull the still images, but it's still not anywhere near acceptable.

Kind of a cool thing to think about. 

 <img src="/img/blinky/buttonblink.gif">