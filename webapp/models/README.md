Well, we need image recognition models to make the magic happen.

You can run `download_and_save_inceptionresnet.py` to download the InceptionResNetV2 checkpoints and save them into the /tmp/ folder.
But first, you need to clone the repository of TensorFlow models so you can use some methods not included in TensorFlow.

`cd ~`
`git clone https://github.com/tensorflow/models.git`

`cd /path/to/webapp/models`
`python download_and_save_inceptionresnet.py`
`mkdir inception_resnet_v2`
`mv /tmp/inception_resnet_v2/model* ./inception_resnet_v2/`