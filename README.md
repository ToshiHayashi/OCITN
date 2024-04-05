# OCITN
In this repository, we provide source code for "Less complexity one-class classification approach using construction error of convolutional image transformation network".
The paper is published from Information Sciences (Elsevier). https://www.sciencedirect.com/science/article/pii/S0020025521001079


## Overview
One-class classification is a machine learning problem, where training data has only one class. The objective is to determine if the input data is seen class or unseen class.
Traditional deep learning algorithms are not suitable for this task since the algorithm can predict only class in training data. In this paper, the one-class classification algorithm using construction error of image transformation network (OCITN) is proposed. In particular, image transformation network (ITN) is introduced as a subtask, which transforms input image into one image, namely goal image. Moreover, the error of ITN, namely construction error (CE), is computed as a distance metric between the goal image and model output. ITN model is trained using only one-class images and is applied for testing images. Since the model is trained with only one-class images, the CE for one-class is small relative to other classes. Thus, one-class classification is made determining CE is large or small.

![OCITN](https://user-images.githubusercontent.com/32119345/108633647-aa9aac80-74b8-11eb-9bc4-ad2fb2dc0036.png)






## Please cite the following paper.
Toshitaka Hayashi, Hamido Fujita, Andres Hernandez-Matamoros, Less complexity one-class classification approach using construction error of convolutional image transformation network, Information Sciences, Volume 560, 2021, Pages 217-234, https://doi.org/10.1016/j.ins.2021.01.069
