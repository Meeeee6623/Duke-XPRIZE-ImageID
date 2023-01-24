# Identification-of-Species by Images/Video
Repository for Rainforest Engineering/Sp23 XPRIZE Identification of 
Species Team.
Includes Identification tools for and Video
* note: Please make sure: 
  * video files are in .mp4 

## Table of Contents
* [Technologies](#technologies)
* [Installation](#installation)
* [Video: General info](#video-general-info)
* [Video: Instructions](#instructions-video)

## [Technologies](#technologies)
This project is made possible thanks to: 
* Python 3
* Google Cloud Vision
* Dr. Matrin Brooke and the Duke University XPRIZE team

## [Installation](#installation)
1. Install Python on your computer. 
2. Clone this repository onto your computer.
3. Install the following programs onto your computer:
* Install the following packages if needed using pip install: 
      pandas, os, scipy, pydub, shutil, math,
      pillow, google.cloud, google-cloud-vision, opencv-python, 
      scikit-image opencv-python imutils

## [Video: General info](#video-general-info)
The python codes you will need analyzing and sorting video data from field/drone 
recordings and descriptions of what they do follow below:

* FilterVideos.py: Crops given video into smaller images sections and picks
  the most quality unique images to analyze.
* FilterImages.py: Crops the images gotten from FilterVideos.py to only contain
  the object of interest and sorts them into labeled folders. 
  
## [Video: Instructions](#instructions-video)
1. Complete #installation
2. Place your videos into the folder called "input"
3. Go to terminal and cd into the folder containing the code. 
4. In the terminal type: python FilterVideos.py 
5. In the terminal type: python FilterImages.py 
6. View images if you so desire in: "Labeled Cropped Images"
