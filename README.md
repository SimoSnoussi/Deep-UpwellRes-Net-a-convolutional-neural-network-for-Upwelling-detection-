# Deep residual U-Net based model for Upwelling detection in Sea Surface Temperature (SST) satellite images
This is a Keras based implementation of a deep learning model that combines residual network and U-Net like architecture to perform Upwelling extraction in SST images.

# Implementation 
* U-Net like architecture with residual units is used to perform segmentation.
* The dataset consists of satellite-derived Sea Surface Temperature (SST) images provided by MODIS Terra satellite and their corresponding labels. 
* The SST used can be found in http://oceancolor.gsfc.nasa.gov/
* UpwellRes-Net is compared to a simple U-Net based structure (Upwell-Net).

# Network architecture of Upwell-Net 
![](upwellres_net.png)
