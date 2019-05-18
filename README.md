# Data-Science_Dog-Breed-Classifier
A dog breed classifier to identify the breed of a provided dog image out of 133 categories.

### Project Summary:
The objective of this project is to build a dog breed classifier that provided an image can first detect whether a dog (or a human) is present in the image. Once it's detected, the next step is to classify the dog (or human) into one of the 133 dog breed categories.
The project makes use of pre-trained convoluted neural networks (VGG16 and Resnet50) that it borrows learning from and then, uses a fully connected layer to convert the output into our 133 dog breed categories.

### Instructions:
To predict the breed of a dog, 
1. Place your test image in the images folder.
2. Pass the image file path to the predict_breed() function in the dog_app iPython notebook.
3. The output will tell whether a dog or human was detected and based on that, what breed they are (for a dog) or resemble (for a human).

### File description:
1. dog_app.ipynb
	- This python notebook contains the code for dog and human detection in the provided image.
  - It also contains a few implementations of different CNNs trained to identify the dog breed of the provided image.

2. extract_bottleneck_features.py
	- A support python file that contains the functions to extract the bottleneck features for the CNNs used in the actual python notebook.
	
### Medium Blog Post
We also wrote a medium blog post on the same topic going further into the details of our work which can be found here - https://medium.com/@preetkamalsingh1992/dog-breed-classifier-udacity-data-science-1dd5042fd4c1.
