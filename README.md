What is Gif Maker?
=================

A Mac Automator application that creates a gif out of any files that are dropped onto it.


Release Notes
=================

The current and only version:
- handles filenames with spaces
- names the resulting GIF with a simple timestamp
- creates a GIF with a 1 second delay between images


Dependencies
=================

- Mac OSX – Works on Mavericks (10.9), but may have compatibility issues with other versions of Applescript.

- ImageMagick (http://www.imagemagick.org/) – This is image manipulation software that you can run through the command line. The Automator application uses the "convert" command to turn all the images dropped onto it into a single gif.


Opportunities for Enhancement
=================

- Allow users to drop an entire folder of images onto Gif Maker
- Allow users to create multiple GIFs at one time, perhaps one for each group of similarly named images
- Base resulting GIF name off of supplied images
