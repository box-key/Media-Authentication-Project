# Description

This program takes CASIA2 dataset as input and generates new dataset in the following format: </br>
Create directory for each Authentication image. Each Authentication directory contains the orginal and tampered version of the image.

(i.e.)
- Au image 1
  - Tp image1  
  - Tp image1 </br>
  ...</br>
  - Tp image1

...

- Au image N
  - Tp imageN
  - Tp imageN</br>
  ...</br>
  - Tp imageN

# How to run

1. Create a new folder to store formatted dataset
2. Open program and go to the Initialization cell
3. Specify the path to original Au, original Tp, and new folder
4. Run program cell by cell

* It takes several minutes to finish the entire program

# How it works

Basically, this program takes advantage of the fact that each tampered image contains its src ID in its name. </br>
Detail: https://github.com/namtpham/casia2groundtruth

This program follows the steps below.

1. Create src folder for each Au image in a directory specified by the user.
2. Copy each Au images from the original folder to corresponding src folder.
3. Au's part is done. Then, go to Tp folder.
4. Extract src ID from each Tp image.
5. Insert Tp images into its corrensponding src folder.
6. Done. Run debugging cells to check the result.


