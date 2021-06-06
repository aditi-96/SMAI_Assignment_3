Implemented the following networks using keras library
## cnn.ipynb
- Implemented fully functioning CNN for classification on CIFAR-10 dataset.
- Experimented with number of layers, optimizer, loss, batch normalization, etc.
- Test accuracy of 58.09 achieved with 2 blocks of `Conv2D->BatchNorm2D->MaxPooling2D` and one dense layer at the end.

## autoencoder.ipynb
- Implemented fully functioning autoencoder to be used on MNIST Dataset.
- Result: ![autoencoder](https://drive.google.com/uc?export=view&id=1UIHQbAUMbzRbxirSyUszuentpIGYl9gl)
- Experimented with optimizer and size of encoded image.

## mlp.ipynb
- Implemented a Multilayer Perceptron for classification on MNIST dataset
- Achieved an accuracy of 97.78 with optimized SGD w/o momentum
- Experimented with different optimizers

## siamese.ipynb
- Implemented a Siamese network on MNIST dataset
- Achieved validation accuracy of 69.72 for contrastive loss in 10 epochs
