# Applied Machine Learning & Deep Learning

A collection of applied machine learning and deep learning models focusing on supervised classification, unsupervised clustering and generative computer vision. 

### Tech Stack
Python, TensorFlow, Keras, scikit-learn, NumPy, Pandas.

### Architectures & Methodologies
*   **Supervised NLP & Classification:** Implemented Dense Neural Networks (MLP) for binary sentiment analysis (IMDB corpus) and multi-class hardware pricing prediction. Engineered custom One-Hot Encoding vectorization for variable-length text sequences.
*   **Computer Vision & Denoising:** Built Convolutional Autoencoders (Conv2D, MaxPooling2D, UpSampling2D) to isolate signal from noise in corrupted image datasets, utilizing binary crossentropy to optimize pixel-intensity reconstruction.
*   **Unsupervised Clustering:** Applied K-Means and DBSCAN algorithms for customer segmentation. 

### Engineering Highlights
*   **Hyperparameter Optimization:** Designed manual Grid Search pipelines to tune learning rates, batch sizes and network depth, strictly balancing model capacity against early overfitting.
*   **Data Pipeline:** Enforced rigorous pre-processing, including Interquartile Range (IQR) outlier removal and StandardScaler normalization to maintain geometric integrity in distance-based clustering.
