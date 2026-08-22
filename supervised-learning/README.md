# Supervised Learning: Mobile Pricing & Concrete Strength

This directory contains supervised machine learning models developed for multi-class classification (predicting mobile phone price ranges based on hardware specs) and regression/estimation tasks (predicting concrete strength).

### Algorithmic & Engineering Highlights
* **Feature Engineering & Dimensionality Reduction:** Analyzed correlation matrices to eliminate redundant variables, explicitly combining hardware dimensions (e.g., merging `px_height` and `px_width` into a single `pixeles_totales` vector) to streamline the feature space.
* **Data Sanitization & Scaling:** Implemented `StandardScaler` to normalize features with vastly different magnitudes (e.g., battery mAh vs. clock speed), ensuring gradient stability and uniform distance metrics during training.
* **Exploratory Data Analysis (EDA):** Built comprehensive visualization pipelines (heatmaps, boxplots, scatter matrices) to identify class distributions, feature relationships, and potential hardware outliers prior to modeling.
