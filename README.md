# My-ResNet
This is the docker image auto-build repository for Docker-Hub.
The image provide the base official resnet model to use.
(ResNet-50 v2 (fp32, Accuracy 76.47%))

## Tensorflow
The base image is tensorflow/serving.

##  Recommend Usage
docker run -p 8500:8500 -p 8501:8501 --name myresnet blackwpz/my-resnet
