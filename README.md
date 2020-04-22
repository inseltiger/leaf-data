# leaf-data

This repo contains two datasets

1. leaf-images-with-pascal-voc-annotations.zip is a dataset of 200 leaf images with their bounding boxes annotated in PASCAL VOC.
Here multiple leafs per image are annotated.

2. single-leaf-images-with-pascal-voc-annotations.zip is a dataset of the same images, however only the most central leaf is annotated here.

# Analysis

I used the data to identify leafs in images and crop the images down to the bounding box of the leaf. 
This was in order to augment a dataset of apple leaf images with diseases for better classification of the disease
using a deep neural network. 

See the data augmentation here: Plant_Pathology_2020_Experiments_with_cropping.ipynb
