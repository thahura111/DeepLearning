# Project Name
Implement a Multiclass classification model using a custom convolutional neural network in TensorFlow.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Different models are tried to detect the melanoma using image classification.
- Base model : 
	A CNN model is created with the below architecture :
		- Batch size = 32
		- image size = 180*180
		- Train set = 0.8 and validation set =0.2
		- Epocs = 20 
		Model architecture: 
			- Conv2D with 32 features and 3*3 filters and padding 
			- Relu activation
			- Conv2D with 32 features 
			- Max Pooling with pool size 2*2
			- Dropout rate : 0.25
			- Conv2D with 64 features and 3*3 filters and padding 
			- Relu activation
			- Conv2D with 32 features 
			- Max Pooling with pool size 2*2
			- Dropout rate : 0.25
			- Flatten
			- Dense layer with 512 
			- Relu activation
			- dropout rate : 0.25
			- Dense layer with number of classes, ie, 9
			- softmax activation 
		
- Model 2 : 
	- normalization
	- Augmentation schemes
	
- Model 3 : 
	- Handle data imbalance
	- normalization
	- Augmentation



## Conclusions
Model 3 has increase the accuracy and is not overfitted.




## Technologies Used
- TensorFlow



## Acknowledgements



## Contact
Created by [@thahura111] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->