# How to split long pictures (such as panoramas) into multiple pictures 
## On windows:
### Install ImageMagick
https://imagemagick.org/script/download.php#windows

### Run the line below on command line:
> magick convert -crop WIDTHxHEIGHT ORIGINAL_FILE_NAME.jpg SPLIT_OUTPUT_%d.jpg



