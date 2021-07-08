# Chest-X-ray-Abnormalities-Detection
Automatically localize and classify thoracic abnormalities from chest radiographs
##############################################################################################

we are classifying common thoracic lung diseases and localizing critical findings. This is an object detection and classification problem.
For each test image, you will be predicting a bounding box and class for all findings. If you predict that there are no findings, you should 
create a prediction of "14 1 0 0 1 1" (14 is the class ID for no finding, and this provides a one-pixel bounding box with a confidence of 1.0).
The images are in DICOM format, which means they contain additional data that might be useful for visualizing and classifying.
