# Intel Computer Vision SDK | Hello World Tutorial

## Prerequisite Checklist
- [ ] Verify HW compatibility
- [ ] Install OpenCL and other dependencies
- [ ] Install the CV SDK and set environment variables

## Install the Hello World tutorial support files (trained models, videos, images)

#### 1. Create new directory opt/intel/tutorials/cvsdk

	```mkdir opt/intel/tutorials/cvsdk```

#### 2. Navigate to the new directory

	```cd opt/intel/tutorials/cvsdk```

#### 3. Download/clone tutorial files to current directory (opt/intel/tutorials/cvsdk) which includes the
following sub-directories: models, samples, videos, images

	```git clone https://github.com/intel-iot-devkit/computer-vision-hello-world.git```

# Part 1: How to optimize and deploy a deep learning model for Pedestrian Detection (~15mins)

## Introduction and Learning Goals

#### 1. Introduction and overview of what you’re about to learn and why you would care

	This tutorial will walk you through the basics of using the Deep Learning Deployment Toolkit’s Inference Engine (included in the Intel® Computer Vision SDK). Here, inference is the process of using a trained neural network to infer meaning from data (e.g., images). In the code sample that follows, a video (frame by frame) is fed to the Inference Engine (our trained neural network) which then outputs a result (classification of an image). Inference can be done using various neural network architectures (AlexNet*, GoogleNet*, etc.). 

	This example uses a Single Shot MultiBox Detector (SSD) on GoogleNet model. The Inference Engine requires that the model be converted to IR (Intermediate Representation) files. This tutorial will walk you through the basics taking an existing model (GoogleNet) and converting it to IR (Intermediate Representation) files using the Model Optimizer.
	
#### 2. Provide an example of what success looks like in this module

	> Show a side-by-side comparison of the pedestrian video clip: original vs with bounding boxes
	
#### 3. Conceptual diagram: E2E video application developer journey map

	> (continue to show this throughout the module as it changes? i.e. ‘you are here’)
