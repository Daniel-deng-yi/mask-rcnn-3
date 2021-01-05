# mask-rcnn-3
1、Mask R-CNN for object detection and instance segmentation on keras and TensorFlow

    Python 3.4+
    TensorFlow 1.3+
    Keras 2.0.8+
    Jupyter Notebook
    Numpy, skimage, scipy, Pillow, cython, h5py
    opencv 2.0

2、MS COCO Requirements:

To train or test on MS COCO, you'll also need:

    pycocotools (installation instructions below)
    MS COCO Dataset
    Download the 5K minival and the 35K validation-minus-minival subsets. More details in the original Faster R-CNN implementation.

3、Download pre-trained COCO weights (mask_rcnn_coco_humanpose.h5) from the release page 4、(Optional) To train or test on MS COCO install pycocotools from one of these repos. They are forks of the original pycocotools with fixes for Python3 and Windows (the official repo doesn't seem to be active anymore).

    Linux: https://github.com/waleedka/coco
    Windows: https://github.com/philferriere/cocoapi. You must have the Visual C++ 2015 build tools on your path (see the repo for additional details)
