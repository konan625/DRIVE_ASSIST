
Drowsiness Detection - v2 augmented-v1
==============================

This dataset was exported via roboflow.ai on December 22, 2021 at 5:41 PM GMT

It includes 1230 images.
2 are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Fit (white edges))

The following augmentation was applied to create 3 versions of each source image:
* Randomly crop between 0 and 20 percent of the image
* Random rotation of between -10 and +10 degrees
* Random shear of between -5° to +5° horizontally and -5° to +5° vertically
* Random brigthness adjustment of between -10 and +10 percent
* Random exposure adjustment of between -10 and +10 percent
* Random Gaussian blur of between 0 and 0.5 pixels


