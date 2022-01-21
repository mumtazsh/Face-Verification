# Face-Verification

This repository implements a Resnet-based CNN architecture for face recognition and face verification tasks. In order to train the model, both softmax loss and center loss are jointly used as proposed in this [paper](https://kpzhang93.github.io/papers/eccv2016.pdf). 

This architecture is implemented using Pytorch and the dataset consists of ~400,000 face images (size ~1GB). The model is trained using AWS EC2 instances.
