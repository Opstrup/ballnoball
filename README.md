
# Ball / No-ball - A toy example on real image data

Binary classification example with real images.

Install guide:

 Install linux (Ubuntu 16.04)
 Install anaconda - https://www.tensorflow.org/install/install_linux#InstallingAnaconda
 conda create -n tensorflow
 source activate tensorflow
 (notice we change environment)
 pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.3.0-cp27-none-linux_x86_64.whl
 git clone http://github.com/recoord/ballnoball 
 cd ballnoball
 python ballnoball.py

Monitor using tensorboard from other terminal:

source activate tensorflow
(notice we change environment)
cd ballnoball
tensorboard --logdir tensorboard
browse to 127.0.0.1:6006


Jesper Taxbøl
jesper@veo.co
