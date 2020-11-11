# ImagePreprocessing
This repository is a collection of useful image preprocessing tools including text/object-centering, image enhancement, and contour extraction using ```python-opencv```. The python scripts are designed to be used for preprocessing images, particularly for better OCR. 

### Contour Extraction of an Image
Very useful tool for the extraction of objects and their boundaries inside an image. The code extracts all objects within the image with their constraints and further save them all in original form, enabling to extract digits or letter for OCR

### Centering the object
Setting a single object in the center of the image in binarized form. It is designed for putting the  single object in the center of the image, particularly  for data scientists to align the letters or digits within the image constraint to prepare a suitable dataset for OCR. It is only for the single object as it is binarized for background to 0 and foreground to 255. 

### Image Enhancement
In this section, you can find useful python scripts for image enhancement like morphological_operators, image_blurring, image_gradient, increasing brightness and contrast 
