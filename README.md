[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

## Deep Learning Project ##

In this project, you will train a deep neural network to identify and track a target in simulation. So-called “follow me” applications like this are key to many fields of robotics and the very same techniques you apply here could be extended to scenarios like advanced cruise control in autonomous vehicles or human-robot collaboration in industry.

## Write Up ##

### Fully Convolutional Neural Network Model

![Network Model](figures/network1.png)

An encoder-decoder structure of a fully convolutional neural network (FCN) is implemented in the project.


| Tables   |      Are                                                     |  Score |
|----------|:------------------------------------------------------------:|-------:|
| Baseline |  Learning Rate = 0.002; Batch Size = 100, Num of Epochs = 50 | 0.403  |
| Trial 1  |  Num of Epochs = 10       |   0.002  |
| Trial 2  |  Learning Rate = 0.0025   |   0.355  |
| Trial 3  |  Learning Rate = 0.0015   |   0.330  |
| Trial 4  |  Batch Size = 50          |   0.399  |
| Trial 5  |  Three-Layer Network      |   0.395  |
