# Image-Classification

Image Classification is the task of extracting features and classifying image into one of the several categories. Many pre-trained networks like Inception, VGG-NET, Xception exists which are trained on ImageNet dataset. We can work with this networks using [keras](https://www.pyimagesearch.com/2017/03/20/imagenet-vggnet-resnet-inception-xception-keras/). This networks can be used in our classification task so that with the help of it's weights and biases one requires less computation compared to building network from scratch. But in order to use the network one must also consider the size and similarity of data between the images on what pre-trained network is build and that of yours. Depending on the size and similarity there exists different approaches to this task. The following figure explains the approaches.

![image](https://user-images.githubusercontent.com/20052459/45668768-9f9aff80-bb3b-11e8-84b8-2a499ac0c87c.png)

### Implementation

The project implements various techniques in image classification for classifying [UCMerced_LandUse dataset](http://weegee.vision.ucmerced.edu/datasets/landuse.html). It uses VGGNET pre-trained network in keras. The project experiments by building model from scratch, using CNN as feature extractor and also fine tuning the network by freezing initial few layers of CNN.

### References
[Transfer learning & The art of using Pre-trained Models in Deep Learning](https://www.analyticsvidhya.com/blog/2017/06/transfer-learning-the-art-of-fine-tuning-a-pre-trained-model/)

[Inception](https://towardsdatascience.com/a-simple-guide-to-the-versions-of-the-inception-network-7fc52b863202)

[Xception](https://www.kdnuggets.com/2017/08/intuitive-guide-deep-network-architectures.html/2)

[VGGNET](https://machinelearningmastery.com/use-pre-trained-vgg-model-classify-objects-photographs/)
