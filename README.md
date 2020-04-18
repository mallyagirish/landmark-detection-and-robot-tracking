# Landmark Detection & Robot Tracking (SLAM)

This project was completed as part of Udacity's Computer Vision Nanodegree program.

## Project Overview

In this project, you'll implement SLAM (Simultaneous Localization and Mapping) for a 2 dimensional world! You’ll combine what you know about robot sensor measurements and movement to create a map of an environment from only sensor and motion data gathered by a robot, over time. SLAM gives you a way to track the location of a robot in the world in real-time and identify the locations of landmarks such as buildings, trees, rocks, and other world features. This is an active area of research in the fields of robotics and autonomous systems. 

*Below is an example of a 2D robot world with landmarks (purple x's) and the robot (a red 'o') located and found using *only* sensor and motion data collected by that robot. This is just one example for a 50x50 grid world; in your work you will likely generate a variety of these maps.*

<p align="center">
  <img src="./images/robot_world.png" width=50% height=50% />
</p>

The project will be broken up into three Python notebooks; the first two are for exploration of provided code, and a review of SLAM architectures:

__Notebook 1__ : Robot Moving and Sensing

__Notebook 2__ : Omega and Xi, Constraints 

__Notebook 3__ : Landmark Detection and Tracking 


## Project Instructions

All of the code and resources for the project are in this repository. Before you can get started coding, you'll have to make sure that you have all the libraries and dependencies required to support this project.

### Local Environment Instructions

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/mallyagirish/landmark-detection-and-robot-tracking.git
cd landmark-detection-and-robot-tracking
```

2. Create (and activate) a new environment (named `cv-ml`, for example) with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	- __Linux__ or __Mac__: 
	```
	conda create -n cv-ml python=3.6
	source activate cv-ml
	```
	- __Windows__: 
	```
	conda create --name cv-ml python=3.6
	activate cv-ml
	```
	
	At this point your command line should look something like: `(cv-ml) <User>:landmark-detection-and-robot-tracking <user>$`. The `(cv-ml)` indicates that your environment has been activated, and you can proceed with further package installations.

6. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```


## Notebooks

1. Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```shell
cd
cd landmark-detection-and-robot-tracking
```

2. Open the directory of notebooks, using the below command. You'll see all of the project files appear in your local environment; open the first notebook and follow the instructions.
```shell
jupyter notebook
```

3. Once you open any of the project notebooks, make sure you are in the correct `cv-ml` environment by clicking `Kernel > Change Kernel > cv-ml`.


LICENSE: This project is licensed under the terms of the MIT license.
