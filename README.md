# Remove Image Background with Python

### Portrait Segmentation using Tensorflow

This script removes the background from an input image. You can read more about segmentation [here](http://colab.research.google.com/github/tensorflow/models/blob/master/research/deeplab/deeplab_demo.ipynb)

### Setup
The script setup.sh downloads the trained model and sets it up so that the seg.py script can understand. 
>	./setup.sh

### Working
Go ahead and use the script as specified below, to execute fast but lower accuracy model:
>	python3 main.py sample.jpg sample.png 

For better accuracy, albeit a slower approach, go ahead and try :
>	python3 main.py sample.jpg sample.png ultra

### Dependencies
>	tensorflow, PIL or Pillow, numpy

### Sample Result
Input: 
![alt text](https://github.com/ijagjeet/remove-image-background-with-python/raw/master/sample.jpg "Input")

Output without ultra: 
![alt text](https://github.com/ijagjeet/remove-image-background-with-python/raw/master/sample.png "Output")

Output with ultra: 
![alt text](https://github.com/ijagjeet/remove-image-background-with-python/raw/master/sample-v2.png "Output")