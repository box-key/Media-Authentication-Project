# Description
This program makes two folders: the one contains all the original images and the another contains all the modified images.

# How to run

1. Run "Format CASIA2" method to create subdirectories for all the original images with their tampered ones.
2. Open program and go to the Initialization cell
3. Specify the path to original Au, original Tp, and new folder
4. Run program cell by cell

# How it works

1. Remove all the subdirectories which only have original image.
2. For each subdirectory, transfer the first image(original one) into original folder.
3. Then, transfer all the other images into modified folder with the name, "name of original" + "unique # in the subdirectory". </br>
(e.g.) Dog_1, Dog_2, ..., Dog_n, where n is the # of modified images based on Dog.
