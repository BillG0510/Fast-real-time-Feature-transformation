# Fast-real-time-Feature-transformation
Python, PyTorch
- System consists of two components: an image transformation network  and a loss network  
- Selected a pretrained  VGG network as loss network and convert it to FCN 
- Consturcted a style transformation ResNet and used a style picture, input images and desired output images to trained the style transformation net by SGD
- Used two criteria:feature reconstruction loss' and 'style reconstruction loss' to update the weight
<p align="center">
    <img src="images/style-images/mosaic.jpg" height="200px">
    <img src="images/content-images/amber.jpg" height="200px">
    <img src="images/output-images/amber-mosaic.jpg" height="440px">
</p>
