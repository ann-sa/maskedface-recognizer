# Realtime Masked Face Recognizer

The project is based on the [FaceNet](https://arxiv.org/abs/1503.03832).

## Inspiration
The project is heavily inspired by
* [FaceNet](https://github.com/davidsandberg/facenet)
* [MediaPipe](https://github.com/google/mediapipe)
* [Android LibSVM](https://github.com/yctung/AndroidLibSVM)
* [Tensorflow Android Camera Demo](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/android)

The code can recognize 20 people's masked faces. Click [(here)](https://github.com/ann-sa/face-recognizer/blob/master/app/src/main/assets/label) to see labels.
Also, you can add new person using photos.

## Pre-trained model
from davidsandberg's facenet

| Model name      | LFW accuracy | Training dataset | Architecture |
|-----------------|--------------|------------------|-------------|
| [20180402-114759](https://drive.google.com/open?id=1EXPBSXwTaqrSC0OhUdXNmKSh9qJUQ55-) | 0.9965        | VGGFace2      | [Inception ResNet v1](https://github.com/davidsandberg/facenet/blob/master/src/models/inception_resnet_v1.py) |

from MediaPipe
  * [TFLite model](https://github.com/google/mediapipe/tree/master/mediapipe/models/face_detection_front.tflite)
  * Paper: ["BlazeFace: Sub-millisecond Neural Face Detection on Mobile GPUs"](https://sites.google.com/corp/view/perception-cv4arvr/blazeface)
