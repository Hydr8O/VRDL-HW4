# VRDL-HW4
Reproducing submission
=======================
1. Clone repository ```git clone https://github.com/Hydr8O/VRDL-HW4```
2. Create conda environment ```conda create -n hw4_env python=3.7 -y```
3. Activate environment ```conda activate hw4_env```
4. Install dependencies ```pip install -r requirements.txt```
6. Download pretrained model https://drive.google.com/file/d/1zLLC5smvaUs9oI-eLohp7bp2ULSXY8ET/view?usp=sharing
7. Create output directory ```mkdir output```
8. Put images for super resolution into data/testing_lr_images
9. Launch super resolution with ```python inference.py```. 
  The output will be in output directory
