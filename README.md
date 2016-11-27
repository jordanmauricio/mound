#Mound
######Some features are deprecated, explained below.

Mound is a music visualizer, that uses face tracking technology in order to control the music. All of this works inside the browser, through JavaScript with the [P5](https://p5js.org/) and [clmtracker](https://github.com/auduno/clmtrackr) libraries as dependencies. HTML5 is also used in order to receive data and access for the webcam. 

However, recently Google Chrome has deprecated the getUserMedia() function on insecure (anything *not* HTTPS) servers which means that this product doesn't work on a regular HTTP server anymore. And to get HTTPS on a small-time server isn't the easiest thing in the world sadly, but how the product works can be seen below in the YouTube video which breaks down how it was built as well. 

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YS1i2IGoFsc
" target="_blank"><img src="http://img.youtube.com/vi/YS1i2IGoFsc/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>