# Deep Learning: Denoising Autoencoders & NLP Classification

This directory implements advanced neural network architectures using TensorFlow/Keras, tackling both computer vision (extracting signal from Gaussian noise) and Natural Language Processing (binary sentiment analysis).

### Algorithmic & Engineering Highlights
* **Convolutional Autoencoders:** Engineered an asymmetric compression pipeline using `Conv2D` and `MaxPooling2D` to discard spatial noise, followed by `UpSampling2D` layers to reconstruct structural dimensions pixel-by-pixel.
* **Sequence Vectorization:** Built custom One-Hot Encoding functions to transform variable-length text sequences into fixed-size tensors (10,000 dimensions) suitable for input into Dense network topologies.
* **Hyperparameter Tuning & Regularization:** Designed a manual Grid Search pipeline to evaluate learning rates, batch sizes, and network depth. Identified early overfitting at epoch 5 and successfully mitigated it by scaling the Adam optimizer's learning rate down to 0.0001 with a batch size of 256.
* **Loss Optimization:** Selected `binary_crossentropy` to heavily penalize divergent predictions in both text classification certainty and image pixel-intensity reconstruction.
