# PYTORCH GLASS DETECTOR USING TRANSFER LEARNING.

### Used Pytorch to train and validate the model, check "./src/glass_classifier_training.ipynb".
> To train build the celeba dataset with two classes(glasses and without glasses) and do the test-train split.
follow this directory structure: 
* celeba/
* --- train/
* --------glasses/
* --------wglasses/
* ----val/
* --------glasses/
* --------wglasses/

### Resnet-18 pretrained model from pytorch was as feature extractor which can be easily replaced.
> Replace resnet-18 from the ipynb(models.resent18) and change inputs/code accordingly. 

### Used celeba dataset with ~13k(with glasses) and ~13k (without glasses) as dataset. 
> This dataset can be easily found on the net.

### Resnet-18 can easily manage the task at hand and the pretrained model is available in model directory.

### Use "./src/glass_inference.ipynb" for Inference code on your webcam. 
> Uses OpenCV, MTCNN for face detection. 
