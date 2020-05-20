# Segmentation-ssnet

Semantic segmentation is a natural step in the progression from coarse to fine inference:
- The origin could be located at classification, which consists of making a prediction for a whole input.
- The next step is localization / detection, which provide not only the classes but also additional information regarding the spatial location of those classes.
- Finally, semantic segmentation achieves fine-grained inference by making dense predictions inferring labels for every pixel, so that each pixel is labeled with the class of its enclosing object ore region.

This network was trained on just 200 labelled training images obtained from KITTI pixel-level semantic dataset. 
