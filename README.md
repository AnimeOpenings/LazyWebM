Lazy WebM
=====
### The lazy way to convert video to WebM

A simple batch script that runs through all files in a folder and converts them to WebM files using ffmpeg

### How to use:

* Run convert.bat once to create the folders
* Put video files in the input folder
* Run convert.bat
* ???
* PROFIT (Hopefully)

You can also edit the batch file to change some of the ffmpeg settings if you wish.  
The standard settings create decent 720p video files in most cases, it's overkill for 480p and a little low for 1080p.

(Personally I'd recommend changing "-threads 1" to a higher number if possible, such as 2 for a dual core or 4 if you have a quad-core processor, no matter what quality you wish for)
