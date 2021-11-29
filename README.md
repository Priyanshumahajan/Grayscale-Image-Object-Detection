# Grayscale-Image-Object-Detection
Object detection in dark and low-lit conditions is found to be inaccurate and if pre-trained models are used.
Therefore, the proposed solution is to train YOLOv4 and YOLOv4-tiny on custom dataset of Grayscale images.
For the prelimnary stage of development we only used single class of object i.e car to prove our thoery. The labelled [Datasetv1](https://drive.google.com/file/d/1ypLwiQwgWpqHqJsBPMqvMH35idEMUEns/view?usp=sharing)was used to train the model.
Both YOLOv4 and YOLOv4-tiny are trained on the same data and can be used on both for RGB aswell as Gray inputs of images and videos.
This is possible due to transfer learning of pre-trained RGB model.
