# Description
This program converts all the tif files into jpg files.

# How to run

1. Run "Format CASIA2" method to create subdirectories for all the original images with their tampered ones.
2. Open program and go to the Initialization cell
3. Specify the path to original Au, original Tp, and new folder
4. Run program cell by cell

# How it works

1. Read images in each subdirectory
2. For all the tif files, creates a copy of images with jpg extension.
3. Then, it goes through all the subdirectories again to delete all the tif images. </br>
* Program works this way because it causes an error if it deletes tif file right after creating a jpg version of file.
