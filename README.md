# skin_tone
This is a project about changing the skin tone of model in the images

## 1 pipline
### 1.1 Pretrained
Import the pretrained model parameters into the defined UNET model
### 1.2 test dataset
The dataset contains six model images, Our task is to change the skin tone of the model
### 1.3 inference
The predicted semantic segmentation results are obtained, and then the threshold is set to obtain the region containing skin that should be segmented.For the segmented region, modify the brightness of the pixels in the region

## 2 how to run test.ipynb
Just run test.ipynb while keeping the file location unchanged.
The running steps have been divided in the test.ipynb file, and each step has corresponding comments

## 3 reference
https://github.com/MRE-Lab-UMD/abd-skin-segmentation
