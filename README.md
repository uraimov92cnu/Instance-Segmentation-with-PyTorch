# Instance-Segmentation
A very natural idea is to combine the two together. We want to only identify a bounding box around an object, and we want to find which of the pixels inside the bounding box belong to the object.

In other words, we want a mask that indicates ( using color or grayscale values ) which pixels belong to the same object. An example is shown below:

The class of algorithms that produce the above mask are called Instance Segmentation algorithms. Mask R-CNN is one such algorithm.

- Instance segmentation and semantic segmentation differ in two ways:

- In semantic segmentation, every pixel is assigned a class label, while in instance segmentation, that is not the case.
We do not tell the instances of the same class apart in semantic segmentation. For example, all pixels belonging to the “person” class in semantic segmentation will be assigned the same color/value in the mask. In instance segmentation, they are assigned different values, and we can tell them which pixels correspond to which person. We can see this in the above image.
