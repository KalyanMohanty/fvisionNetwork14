# Square Number takes an integer as an input and prints it square.

## Installation
```pip install fvisionNetwork14```

## Description
version: 1.9.3

modules:
        - image_preprocessing
        - fvNet14
        - plot_accuracy
        - plot_loss
        
Dependancy modules:
        - numpy
        - from tensorflow
        - matplotlib

## How to use?
e.g:
### image_preprocessing
    image_preprocessing(path, image_height = 50, image_width = 50)

### fvNet14
    model_test = fvNet14(image_height = 50, image_width = 50, color_channel = 3, output_layer = 10)
    history = model_test.fit(xtrain,ytrain,epochs=50,validation_data=(xtest,ytest))

## plot_accuracy
    plot_accuracy(history, height = 10, width = 10)

## plot_loss
    plot_loss(history, height = 10, width = 10)
## License

© 2022 Kalyan Mohanty

This repository is licensed under the MIT license. See LICENSE for details.
