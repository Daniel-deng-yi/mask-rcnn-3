# This is an implementation of Mask R-CNN on Python 3,pytorch, and TensorFlow. The model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

Instance Segmentation Sample

The repository includes:

    Source code of Mask R-CNN built on FPN and ResNet101.
    Training code for MS COCO
    Pre-trained weights for MS COCO
    Jupyter notebooks to visualize the detection pipeline at every step
    ParallelModel class for multi-GPU training
    Evaluation on MS COCO metrics (AP)
    Example of training on your own dataset

The code is documented and designed to be easy to extend. If you use it in your research, please consider citing this repository (bibtex below). If you work on 3D vision, you might find our recently released Matterport3D dataset useful as well. This dataset was created from 3D-reconstructed spaces captured by our customers who agreed to make them publicly available for academic use. You can see more examples here.
