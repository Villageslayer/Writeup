# The 4 Step Process of #Training a Model for Detecting Objects in Images

## Step 1:  Create a Dataset:

- ## Dataset Creation in 4 steps :
	- ### 1: Acquire Image  Data: 
		- ### Size:
				At the very least 1000 images
				Resolution: 1080p+
				
		- ### Common Mistake and How to avoid:
				Already at this step it is possible to Mess up the Model by simply Acquiring low Quality Data, meaning low image resolution or simply images that are too compressed and therefore contain artifacting within the image.
				To avoid this simply Choose High Quality PNG or JPEG files with at least 1080x1080 Resolution
	- ### 2: Define your Classes:
			Class Definition can simply summed up by Defining what to detect. 
	- ### 3: Label your images:
			This is the very tedious part of drawing rectangles around the objects the Model is supposed to detect.
			This takes multiple Hours and is quite Boring.
			Side note on polygons: While Possible they are overkill for what this project wants to achieve.
	- ### Create a data.yaml
			This contains the image file paths relative to itself aswell the the Detection Classed Defined Earlier.

## Step 2: ==**Find FREE/Cheap GPU resources...**==

## Step 2.1:  Train the Model.
- ###  


