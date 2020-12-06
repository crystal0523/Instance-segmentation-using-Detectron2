# Instance-segmentation-using-Detecron2
The purpose of this project is to implement a model for the task of instance segmentation using Tiny PASCAL VOC dataset. Detectron2 platform is used for this task. In particular, the model used is Mask R-CNN with ResNet50 as backbone. ImageNet pre-trained weights are used as a starting point for training
## Dataset
We use Tiny PASCAL VOC dataset in this project, including 1349 training images and 100 test images

------------------
<p align="center">
  <img src="2007_000033.jpg">
</p>

<p align="center">
  <img src="2007_000129.jpg">
</p>

<p align="center">
  <img src="2007_000175.jpg">
</p>

-------------------


## Environment

 ```
!pip install -U torch==1.5 torchvision==0.6 -f https://download.pytorch.org/whl/cu101/torch_stable.html
!pip install cython pyyaml==5.1
!pip install -U 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'
!pip install detectron2==0.1.3 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/index.html
  ```
## Train
## Results
------------------
<p align="center">
  <img src="test2.png">
  <img src="test4.png">
  <img src="test5.png">
</p>

-------------------


## Credits
1) https://colab.research.google.com/drive/16jcaJoc6bCFAQ96jDe2HwtXj7BMD_-m5#scrollTo=7unkuuiqLdqd
