## Cancer cells detection - Image recognition - Deep Learning  
For the actual analysis, modeling and data transformation please refer to : https://github.com/Folongton/P6-DL-TNT/blob/master/TNT%20Project/TNT_project.ipynb  

What was done :   
1. Picture preprocessing and augmentation via tensorflow and Pytorch - slicing and creation of new images with augmentation. ( We were given only 1 picture with dims of 6000x5000 pixels)
2. Picture preparation - we had to find a way to classify our created images first. Parts of the picture (tunnels) with possible cancer cells were marked by doctors and we had to classify them first before starting training the model.
3. Then training was done with DNN in tensorflow.
