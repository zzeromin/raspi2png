raspi2png
=========

Utility to take a snapshot of the raspberry pi screen and save it as a PNG file

    Usage: raspi2png [-p pngname] [-v] [-w ] [-h ] [-t ] [-d ]
    -p - name of png file to create
    -v - verbose
    -h - image height (default is screen height)
    -w - image width (default is screen width)
    -t - type of image captured
         can be one of the following: RGB565 RGB888 RGBA16 RGBA32
    -d - delay in seconds (default 0)

building
--------

You will need to install libpng before you build the program. On Raspbian

sudo apt-get install libpng12-dev

Then just type 'make' in the raspi2png directory you cloned from github.
