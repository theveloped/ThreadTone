# ThreadTone | a halftone representation of an image made of thread

The process of generating an image with thread is an idea of [Petros Vrellis](http://artof01.com/vrellis/index.html). As I've documented [here](http://www.thevelop.nl/blog/2016-12-25/ThreadTone/) the process is comprised of three steps:
  
  * Image pre-processing (cropping, resizing, etc.)
  * Algorithm to place threads
  * In my case parsing the result to G-Code for automated fabrication

## To use this tool, run:
python threadTone.py -p [image-path] -l [number-of-lines-to-draw] -n [number-of-pins-to-draw-with]

ex: python threadTone.py -p kitten.jpg -l 2000 -n 250  
ex: python threadTone.py -p puppr.png
###### Note: imgPath is a required field, and to give a value to numPins

## A set of two example images can be found below. Please refer to my [blog](http://www.thevelop.nl/blog/2016-12-25/ThreadTone/) for more details.

![Threaded portrait of Poetin](/assets/poetinThreaded.png "Threaded portrait of Poetin")

![Threaded portrait of Angelina](/assets/angelineThreaded.png "Threaded portrait of Angelina")

## License

This script is released under MIT License.
