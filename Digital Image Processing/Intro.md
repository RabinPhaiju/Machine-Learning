# Agenda

1. Image Processing Concept
2. Batch normalization and Regularization
3. Demo on Image Processing

# Data Augmentation

1. Image augmentation artificially creates training images through differentways of processing or combination of multiple processsing, such as random rotation, shifts, shear and flips.

2. Very easy to implement, give good results expecially on small datasets.

3. Easily fits into framework of noise/marginalization.

> ## Why we should do data augmentation?

    1. We may not have a big dataset, so create more data.
    2. It helps in regularizing the network.

## Data Augmentation Techniques

    1. Horizontal flips
    2. Rotation
    3. Crop/Scale
    4. Color jitter
    5. Other Creative techniques
        i. Random mix/combinations of:
            a. transltaion
            b. Rotation
            c. Stretching
            d. Shrearing
            e. lens destortions

# Weight Initialization Techniques
1. Zero initialization
2. Random initialization
3. Xavier initialization
4. He initialization