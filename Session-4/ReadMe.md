# **Architectural Basics**

While haven't exactly followed a sequence for major portion assignment; PFB sequence that seems matching to my thoughts:

1. 3x3 Convolutions,
2. Receptive Field,
3. MaxPooling,
4. 1x1 Convolutions,
5. Concept of Transition Layers,
6. Position of Transition Layer,
7. SoftMax,
8. How many layers,
9. Kernels and how do we decide the number of kernels?
10. Position of MaxPooling,
11. Batch Normalization,
12. Image Normalization,
13. DropOut
14. The distance of MaxPooling from Prediction,
15. The distance of Batch Normalization from Prediction,
16. When do we introduce DropOut, or when do we know we have some overfitting
17. Number of Epochs and when to increase them,
18. Batch Size, and effects of batch size
19. How do we know our network is not going well, comparatively, very early
20. When to add validation checks
21. Learning Rate,
22. LR schedule and concept behind it
23. When do we stop convolutions and go ahead with a larger kernel or some other alternative (which we have not yet covered)
24. Adam vs SGD



Majorly have clubbed 1-10, 11-16 and 17-23 for different experimentations. 

Adam vs SGD is space that can be explore last and/or first; because for certain data sets one gives better performance then other. Here for MNIST based on past experience have focus on utilizing Adam and tried out SGD for 1 example to see if it works well or not.

For last try, performance improvisation with sgd is more linear and requires higher learning rate and more epochs to train high accuracy and where as with adam it always has been fluctuating among optima and relatively faster; because which would prefer adam  as it would have better chance of exploring out of local optima scenarios. 

 









