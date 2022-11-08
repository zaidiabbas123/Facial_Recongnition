# Facial Recongnition using LBPH and opencv

Tried to make a face recognition model using openCv and Local Binary Pattern Histogram algorithm

Local Binary Pattern (LBP) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.

## Steps involved in LBPH

1)Parameters: the LBPH uses 4 parameters:
Radius
neighbour 
Grid x
Grid Y

2. Training the Algorithm: First, we need to train the algorithm. To do so, we need to use a dataset with the facial images of the people we want to recognize. We need to also set an ID (it may be a number or the name of the person) for each image, so the algorithm will use this information to recognize an input image and give you an output. Images of the same person must have the same ID

3.apply LBP

4.Extracting histogram

5.perform recongnition

### OUTPUT

![image](https://user-images.githubusercontent.com/82194617/200524154-74fecbb2-7acc-42ab-957c-ae14a4efd4e6.png)
