# USIS16K

Source code and dataset for our paper “**USIS16K: High-Quality Dataset for Underwater Salient Instance Segmentation**” by Lin Hong,  Xin Wang, Yihao Li, and Xia Wang. 

Created by **Lin Hong**, email: eelinhong@ust.hk or lin.hong@tum.de

## USIS16K dataset
USIS16K is a large-scale dataset comprising 16,151 high-resolution underwater images collected from diverse real-world settings and covering 158 categories of underwater objects. Each image is annotated with high-quality instance-level salient object masks, representing a significant advance in terms of diversity, complexity, and scalability.  
Google drive: [USIS16K](https://drive.google.com/file/d/1SIfpJe7rpeL6ZsRzD9ir0mRsKRYehjxb/view?usp=drive_link) is a high quality large-scale dataset for Underwater Salient Instance Segmentation (USIS). **It is free for academic research, not for any commercial purposes**.

Note: for practical training and reliable test results of deep methods on the USIS16K dataset, there should be enough samples of each category on the training set, validation set (**training set and validation set are merged in TC-USOD baseline**), and test set. Hence we follow the USOD10K split of roughly 7:2:1. Its folder looks like this:

````
   Data
   |-- USIS16K
   |   |-- USIS16K-TR
   |   |-- |-- USIS16K-TR-RGB
   |   |-- |-- USIS16K-TR-GT
   |   |-- USIS16K-Val
   |   |-- |-- USIS16K-Val-RGB
   |   |-- |-- USIS16K-Val-GT
   |   |-- USIS16K-TE
   |   |-- |-- USIS16K-TE-RGB
   |   |-- |-- USIS16K-TE-GT
````



## Benchmark
We retrained several methods in the fields of object detection and instance segementation in the MMdetection. Here is the qualitative evaluation of the methods.
Retrained models will provide soon

## Bibliography entry
If you think our work is helpful, please cite
```
@ARTICLE{10102831,
  author={Hong, Lin and Wang, Xin and Yihao, Li and Xia, Wang},
  journal={ArXiv}, 
  title={USIS16K: High-Quality Dataset for Underwater Salient Instance Segmentation}, 
  year={2025}}
```

## Acknowledgement
We thank the  MMdetection, WaterMask

## Note to active participants

**We hope our work will boost the development of USIS research. As a young research field, USIS is still far from being solved, leaving large room for further improvement** !!! 
