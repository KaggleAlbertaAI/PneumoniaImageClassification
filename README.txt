# This is the readme file

Hi, we will try to classify pneumonia images using deep learning model Mask-RCNN.

Three labels 'Normal', 'Lung Opacity' and 'No Lung Opacity / Not Normal'
are used in dataset. 
{'No Lung Opacity / Not Normal': 11500, 'Normal': 8525, 'Lung Opacity': 8964}
There is a relatively even split between the three classes, with nearly 2/3rd of the data 
comprising of no pneumonia (either completely normal or no lung opacity / not normal)

The Mask-RCNN model has been trained and tested in Microsoft coco project, we will use transfer 
leraning method to load the pre-trained weights into Mask-RCNN model,and training our object 
detection based on this pre-trained model in the later. 
