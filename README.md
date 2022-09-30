# Dog vs Cat Convolutional Neural Network classification


### Data
The model is trained on Kaggle dataset [kernels edition](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data)

### Model
We use Tensorflow 2.0.0 and Keras MobileNetV2 to build our model. The last layer is Softmax with 2 classes (dog and cat). See jupyter notebook `CatvsDogCNN.ipynb` for more details.
![](https://machinethink.net/images/mobilenet-v2/ExpandProject@2x.png)
![](https://machinethink.net/images/mobilenet-v2/Compression@2x.png)

### Training
- The data from the Kaggle dataset is processed to fit into MobileNetV2 input. See jupyter notebook `CatvsDogCNN.ipynb` for more details.

- The model achieved 98% accuracy on train set and 98% on validation set after 5 epochs 
