# Brain tumor segmentation in MRI images using U-Net

Here, I have implemented a U-Net from the paper ["U-Net: Convolutional Networks for Biomedical
Image Segmentation"](https://arxiv.org/pdf/1505.04597.pdf) to segment tumor in MRI images of brain.

### Segmentation Results
The image below shows the segmentation results from some of the images from the test set.

![Brain Tumor Segmentation Results](https://github.com/iamsachinbagale/Brain-Tumor-Segmentation-Using-UNet/blob/main/Images/Segmentation_Results.png)

Comparing the original image, original mask and the predicted mask, the model based on the UNet++ architecture is correctly able to segment the brain tumor location and generate the masks. Though there are some differences seen in the visualizations above, these can be improved with further training and fine tuning the model itself.
