## Problem statement

Presenting gradCAM as a replacement for the usage of anchor boxes and compare with the previous results using the bounding box predictions.



## Approach to the problem:

1. Build three different networks of same architecture
2. Train one network with COCO dataset for approximately 50 epochs. 
3. Generate the grad cam results for the output obtained from the first network. 
4. Use the grad cam output obtained with the first network for training the second network. 
5. This process is repeated for one more trail to get the grad cam replacement of the anchor box



**DATASET**: COCO

**MODELS TO BE CONSIDERED**: Resnet50, Resnet101, Resnet34

**GRADCAM** Function needs to be refined



## Research Area

1. Why are grad cams better than anchor boxes?
2. Better understanding of GRAD CAM.
3. How to use the grad cam map (output) of one network result, to train the other network
4. Replacement of Anchor box with gradCAM (is it possible ?) 
5. Continuous flow of training of multiple networks
6. Address the problem of varying sizes of grad cam as one object, will not have the same size in multiple images.
7. Drawing the bounding box once we have the proper grad cam outputs.



