# Lucas-Kanade-Tracker

## **PROJECT DESCRIPTION**

The aim of this project is to 

Please refer to [Project Report](https://github.com/adheeshc/Lucas-Kanade-Tracker/blob/master/Report/FINAL%20REPORT.pdf) for further description

### Preparing the Input

<p align="center">
  <img src="/Images/Crop.png" alt="Input Prep">
</p>



#### Visualizing Histograms

<p align="center">
  <img src="/Images/avg_histo.png" alt="avg_histo">
</p>
#### 1D Gaussians

<p align="center">
  <img src="/Images/1D_gaussian.png" alt="1D Gaussian">
</p>

### Expectation Maximization from Scratch

<p align="center">
  <img src="/Images/em.png" alt="EM">
</p>

### Learning Color Models


#### 1D EM Implementation for Color Analysis


#### 3D EM Implementation Color Analysis


### Final Buoy Detection


## **DEPENDANCIES**

- Python 3
- OpenCV
- Numpy
- Glob (built-in)


## **FILE DESCRIPTION**

- Code Folder/[AffineLKTracker_Project4_Final.py](https://github.com/adheeshc/Lucas-Kanade-Tracker/blob/master/Code/AffineLKTracker_Project4_Final.py) - This file is used for cropping out our original dataset
- Code Folder/[EXTRA CREDIT - Car_LKAffine_ShiftBrightness.py](https://github.com/adheeshc/Lucas-Kanade-Tracker/blob/master/Code/EXTRA%20CREDIT%20-%20Car_LKAffine_ShiftBrightness.py) - This file is used for implementing the EM for a random set of datapoints

- Datasets folder - Contains 3 folders with frames of the 3 videos - car, human and vase 

- Images folder - Contains images for github use (can be ignored)

- Output folder - Contains output videos

- Report folder - Contains [Project Report](https://github.com/adheeshc/Lucas-Kanade-Tracker/blob/master/Report/FINAL%20REPORT.pdf)

## **RUN INSTRUCTIONS**

- Make sure all dependancies are met
- Ensure the location of the input video files are correct in the code you're running
- Comment/Uncomment as reqd

- RUN AffineLKTracker_Project4_Final.py 
- RUN EXTRA CREDIT - Car_LKAffine_ShiftBrightness.py


