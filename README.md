Objective: 
Perform comprehensive Exploratory Data Analysis (EDA) on the Iris flower dataset to understand feature distributions, inter-feature relationships, class separability, and data quality.
Dataset:
UCI Iris Dataset — 150 samples, 4 continuous numeric features, 3 perfectly balanced species classes, zero missing values.
Methodology:
Dataset loaded via scikit-learn. Pandas used for data inspection and descriptive statistics. Visualizations created with matplotlib and seaborn: scatter plots (feature relationships), histograms (distributions), box plots (outlier detection via IQR method), pair plot (all feature combinations), and correlation heatmap (Pearson r).
Results:
Petal length and petal width exhibited the highest inter-feature correlation (r=0.963) and provided the clearest class separation. Iris Setosa was confirmed linearly separable. Minor outliers detected only in sepal width. Dataset requires no cleaning.
Conclusion: 
The Iris dataset is high-quality and suitable for classification tasks. Petal features are the primary discriminators between species.
Future Work: Apply dimensionality reduction (PCA, t-SNE) for 2D visualization of all 4 features simultaneously. Build a classification model (Task 3 extends these EDA skills).
