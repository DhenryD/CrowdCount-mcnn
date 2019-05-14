# Image-based Crowd Stability Analysis Using Improved Multi-columns Convolutional Neural Network

# Installation
Install pytorch
Clone this repository
We'll call the directory that you cloned CrowdCount-mscnn ROOT

Data Setup
Download ShanghaiTech Dataset from

Baidu Disk: https://pan.baidu.com/s/1FUNQSuezzAQV4e8CDis1yA

Extraction code： 7ous

Create Directory ROOT/data/original/shanghaitech/

Save "part_A_final" under ROOT/data/original/shanghaitech/

Save "part_B_final" under ROOT/data/original/shanghaitech/

cd ROOT/data_preparation/

run create_gt_test_set_shtech.m in matlab to create ground truth files for test data

cd ROOT/data_preparation/

run create_training_set_shtech.m in matlab to create training and validataion set along with ground truth files

Test
Follow steps 1,2,3,4 and 5 from Data Setup

Download pre-trained model files(The best model we have trained):

[pre-trained model] Extraction code：ew22

Save the model files under ROOT/final_models

Run test.py

a. Set save_output = True to save output density maps

b. Errors are saved in output directory

Training
Follow steps 1,2,3,4 and 6 from Data Setup
Run train.py
