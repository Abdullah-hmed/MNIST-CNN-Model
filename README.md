# MNIST-CNN-Model

The model has been trained on the MNIST dataset. The model boasts an accuracy of <98% consistently, taking around 40 seconds of train time on a T4 GPU on Colab.

To train the model, click on `Runtime -> Run All`, and let all the code cells run. Once all the relevant imports have been downloaded, the model will train, and test itself on a digit, and provide its prediction in the title.

### Limitations
Due to the limitations of the MNIST dataset, the model does not perform too well on real life images of handwritten digits. Although this can be overcome by using an online drawing tool, such as this [Etch-A-Sketch Website](https://meerawks.github.io/EtchASketch/). Feed the screenshot of the drawing into the model and it should provide a better output.