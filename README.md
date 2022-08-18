# Finding-most-similar-image

As we are dealing with images, and computers don‘t understand anything but numbers, so we need to convert those images to some unique numbers, and those numbers or attributes should be able to describe the product.
Now we will use the same algorithm to convert our clicked image to those attributes. 
If we use a different algorithm, then we may get some different attributes.
So to implement our image search, we need to do the following: 1. Generate product attributes (features) using an algorithm 2. Using the same algorithm, find attributes of clicked image 3. Find images with attributes similar to clicked image attributes 
The training of neural network consists of two steps:
1.	Forward Propagation 
2.	 Backward Propagation

This type of approach will not always work because of the limitation of neural networks. A simple neural network cannot work with large data or too much information, and images contain too much information to be processed. That‘s why we will be using a modified neural network to process these images and generate features first. So needed CNN rather Pretrained state of art architecture
After generating features of the test image, we will use KNN to find similar images to that of our test image. The neighbour's function will return the indices of the nearest k neighbours

