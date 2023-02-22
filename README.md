# multiview_stereo_net
For 3d reconstruction and dimensions measurement of object 


This network takes as input a batch of 
images with shape (batch_size, 3, height, width)
 where num_views images are concatenated along 
the channel dimension. The network consists of
 three convolutional layers followed by three
 fully connected layers that output the x, y,
 and z 
dimensions of the object.

This dataset class loads the images as 
RGB images, resizes them to 224x224, and normalises 
the pixel values
 to the range [0, 1].


