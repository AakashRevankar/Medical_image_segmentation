# Image segmentation using DN-CNN, U-net and ResNet-18

 This project `task_1_segmentation` is about segmenting the fetal head axis in ultrasound scan and marking the OFD(occipitofrontal diameter) and BPD(biparietal diameter) in fetal head axis.

Also, region properties are used to calculate pixel coordinates for marking the image, which is then overlaid with the mask.

---

## Installation and description 

To install the following program, please download all the files and upload it to google drive.

The program contains three folders named as `model_weights`, `Python_Script`, `Report`. Inside `Python_Script` there is another folder named as `assets`.

The `assets` folder contains the `Data_preprocessing_image_segmentation.ipynb` and all the image dataset required to run the preprocessing.

---
## Procedures involved in datapreprocessing, training and evaluation of models:

1. `Data_preprocessing_image_segmentation.ipynb` is ran on `masks` to create `binary_masks`.

2. `Python_Script` folder has all the training and testing hypothesis.

3. `Train_seg_CNN.ipynb` notebook shows the procedure to train an **DN-CNN network** and saves the weights in model_weights folder as `(segmentation_model_name).pth`format. `Test_seg_CNN.ipynb` notebook loads the test image and gives the output trained from DN-CNN.

4. `Train_seg_Unet.ipynb` notebook shows the procedure to train an **U-net network** and saves the weights in model_weights folder as `(segmentation_model_name).pth`format. `Test_seg_Unet.ipynb` notebook loads the test image and gives the output trained from U-net.

5. `Train_seg_ResNet18.ipynb` notebook shows the procedure to train an **ResNet-18 U-net network** and saves the weights in model_weights folder as `(segmentation_model_name).pth`format. `Test_seg_ResNet18.ipynb` notebook loads the test image and gives the output trained from ResNet-18 U-net.

---

## Methodology and Results

The detailed view of methodology and results is provided in report folder.







