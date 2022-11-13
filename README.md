# Udacity AI Programming with Python Project

## I completed this project during 2022 summer holidays at Inspirit AI .

In this project I used given python Image Classifier to Identify dog to make sure dog show participants are real dogs.
Determined which image classification algorithms works the “best” on classifying images as “dogs” or “not dogs”. 
Identified trade-off between accuracy and runtime i.e. more accurate the algorithm higher likelihood of more time to run with more computational resources.

Used image classification application deep learning model convolutional neural network (CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges; then using these features to identify objects in the images. I used CNN that has already learned the features from a giant dataset of 1.2 million images called ImageNet.

In this project I investigated the three different architectures (AlexNet, VGG, and ResNet) and determine which is best for your application.

## Results Table

<div align="center">

| # Total Images        |   40  |
|-----------------------|:-----:|
| # Dog Images          |   30  |
| # Not-a-Dog Images    |   10  |

</div>


<div align="center">

|   CNN Model Architecture: |   % Not-a-Dog Correct |   % Dogs Correct      |   % Breeds Correct    |   % Match Correct     |
|---------------------------|:---------------------:|-----------------------|-----------------------|-----------------------|
|   ResNet                  |   90.0%               |       100%            |       90.0%           |    82.5%              |
|   AlexNet                 |   100%                |       100%            |       80.0%           |    75%                |
|   VGG                     |   100%                |       100%            |       93.0%           |    87.5%              |

</div>


From the result obtained above, I found “VGG” as the “best” model architecture because of 100% accuracy in classifying "dogs" and "not-a-dog" and had best performance regarding breed classification with 93.3% accuracy.





***
Reference:
1.  https://github.com/udacity/AIPND-revision/blob/master/notes/project_intro-to-python.md
2.  https://realpython.com/working-with-files-in-python/
3.  https://community.esri.com/t5/python-blog/filenames-and-file-paths-in-python/ba-p/893672
4.  https://www.geeksforgeeks.org/python-ways-to-create-a-dictionary-of-lists/
5.  https://realpython.com/python-dicts/
6.  https://realpython.com/python-string-formatting/
7.  https://www.programiz.com/python-programming/methods/string
8.  https://stackoverflow.com/questions/252703/what-is-the-difference-between-pythons-list-methods-append-and-extend
9.  https://www.geeksforgeeks.org/append-extend-python/
10. https://medium.com/analytics-vidhya/cnns-architectures-lenet-alexnet-vgg-googlenet-resnet-and-more-666091488df5
11. https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
12. https://www.kaggle.com/code/kanncaa1/convolutional-neural-network-cnn-tutorial/notebook
13. http://deeplearning.stanford.edu/tutorial/supervised/ConvolutionalNeuralNetwork/
14. https://www.run.ai/guides/deep-learning-for-computer-vision/pytorch-cnn
15. https://www.simplilearn.com/tutorials/deep-learning-tutorial/convolutional-neural-network
16. https://www.youtube.com/watch?v=Jy9-aGMB_TE
17. https://www.analyticsvidhya.com/blog/2018/12/guide-convolutional-neural-network-cnn/
18. https://www.tensorflow.org/tutorials/images/cnn
19. https://developers.google.com/machine-learning/glossary/#convolutional_neural_network

***