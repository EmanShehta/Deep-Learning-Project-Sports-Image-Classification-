# Deep-Learning-Project-Sports-Image-Classification-
Inception	
yes	Train : 99%
Validation:96%
Test(Kaggle):80%

Customized Model(CNN)	
Yes	Train:98%
Validation:77%
Test(Kaggle):78%

VGG 16	
Yes	Train : 97%
Validation:89%
Test : 70%

AlexNet	
Yes	Train:98%
Validation:85%
Test : 69%

Preprocessing Step:
-	Image Resizing.
-	Encoding for Labels to (0, 1, 2, 3, 4, and 5).

Augmentation Process:
-	Random flip.
-	Random Zoom.
-	Random Rotation.
-	Random crop
-	Translation
-	Adjust brightness and darkness 
-	Random noise
-	Blur 
-	Different transforms

Inception 80 % :	
Architecture: 	
-	Inception module:
-	Convolution layer with filters each of them [1x 1].
-	Convolution layer with filters each of them [3x 3].
-	Convolution layer with filters each of them [3x 3].
-	Convolution layer with filters each of them [5x 5].
-	Convolution layer with filters each of them [5x 5].
-	-Maximum pooling layer with pooling size [3x3].
-	Output :- Concatenate the above layers.

Customized Model 78 % (CNN):
Architecture: 	
- Convolution layer with 32 filters each of them [5x 5].
-Maximum pooling layer with pooling size [2x2].
- Convolution layer with 64 filters each of them [5x 5].
-Maximum pooling layer with pooling size [2x2].
- Convolution layer with 128 filters each of them [5x 5].
-Maximum pooling layer with pooling size [2x2].
- Convolution layer with 256 filters each of them [5x 5].
-Maximum pooling layer with pooling size [3x3].
-Maximum pooling layer with pooling size [3x3].
- Flatten layer.
- Dense layer with 64 neurons.
- Drop out 0.2 
- Dense layer with 32 neurons.
- Output layer with 6 neurons
VGG16   70 % :
Architecture:
-	Convolution layer with 64 filters each of them [3X3].
-	Convolution layer with 64 filters each of them [3X3].
-	Maximum pooling layer with pooling size [2x2].
-	Convolution layer with 128 filters each of them[3X3].
-	Convolution layer with 128 filters each of them[3X3].
-	Maximum pooling layer with pooling size [2x2].
-	Convolution layer with 256 filters each of them[3X3].
-	Convolution layer with 256 filters each of them[3X3].
-	Convolution layer with 256 filters each of them[3X3].
-	Maximum pooling layer with pooling size [2x2].
-	Convolution layer with 512 filters each of them[3X3].
-	Convolution layer with 512 filters each of them[3X3].
-	Convolution layer with 512 filters each of them[3X3].
-	Maximum pooling layer with pooling size [2x2].
-	Convolution layer with 512 filters each of them[3X3].
-	Convolution layer with 512 filters each of them[3X3].
-	Convolution layer with 512 filters each of them[3X3].
-	Maximum pooling layer with pooling size [2x2].
-	Flatten layer.
-	Dense layer with 4096 neurons.
-	Drop 0.5   
-	Dense layer with 4096 neurons.
-	Output layer with 6 neurons.
AlexNet 69 % :	
Architecture: 	
- Convolution layer with 96 filters each of them [11x 11].
- Batch normalization 
-  Maximum pooling layer with pooling size [2x2].
-  Convolution layer with 256 filters each of them [5x5].
- Batch normalization 
-  Maximum pooling layer with pooling size [3x3].
- Convolution layer with 384 filters each of them [3x3].
- Batch normalization 
- Convolution layer with 384 filters each of them [1x1].
- Batch normalization
- Convolution layer with 256 filters each of them [1x1].
- Batch normalization
- Maximum pooling layer with pooling size [2x2].
- Flatten layer.
- Dense layer with 100 neurons. 
- Drop 0.5   
- Dense layer with 100 neurons. 
- Drop 0.5   
- Output layer with 6 neurons.

