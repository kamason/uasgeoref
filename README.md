# Georeferencing UAS Images
This directory includes Python scripts for generating world files and projection files for UAS images so images can be projected in the (generally) correct location in GIS software. Note that the images may appear off-location due to the roll or pitch of the aircraft (which this code does not take into account), errors in the geotagged location of the image due to timing of the aircraft GPS and camera being off, or because the images are not orthorectified. The various codes use Exif info for geotagged files or .csv files exported from Agisoft PhotoScan for non-geotagged images, and user input of flight elevation or user input of an SRTM DEM. 

For more informaiton on how to use this code, please email: kmaso270@gmail.com

