# Discovering Emergent Visual Identities in Static Images

## Project Description

This project presents an unsupervised computer vision framework for discovering hidden visual identities in interior design images. Instead of relying on predefined style labels, the system groups visually similar images using a hybrid feature representation that combines deep learning and handcrafted features.

The proposed pipeline extracts semantic, color, and texture information from images, reduces feature dimensionality using PCA, and applies multiple clustering algorithms to reveal meaningful visual patterns.

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Computer Vision Techniques

- Image Preprocessing
- ResNet50 Feature Extraction
- RGB Color Histogram
- Local Binary Pattern (LBP)
- Hybrid Feature Representation
- Feature Standardization
- Principal Component Analysis (PCA)
- t-SNE Visualization

---

## Clustering Algorithms

- K-Means
- Agglomerative Hierarchical Clustering
- DBSCAN

---

## Methodology

The project follows the following pipeline:

1. Load interior design images.
2. Preprocess images by resizing, normalization, and RGB conversion.
3. Extract three complementary feature types:
   - Deep features using ResNet50
   - Color histogram features
   - Texture features using LBP
4. Combine all extracted features into a hybrid representation.
5. Standardize features and reduce dimensionality using PCA.
6. Apply multiple clustering algorithms.
7. Evaluate clustering quality using quantitative metrics and qualitative visualization.

---

## Results

- Successfully discovered **three emergent visual identities** from interior design images.
- K-Means achieved the best clustering performance among the evaluated methods.
- PCA reduced the feature space while preserving important visual information.
- t-SNE visualization demonstrated meaningful separation between discovered visual identities.
- Heatmap and dendrogram analysis further improved the interpretation of clustering results.

---

## Tools

- Google Colab
- Jupyter Notebook
- Kaggle Dataset

---

## Project Structure

```
├── Dataset
├── Preprocessing
├── Feature Extraction
├── PCA
├── Clustering
├── Evaluation
├── Visualization
└── Final Report
```

---

## My Contribution

My primary contribution to this project was implementing the **Hybrid Feature Extraction** module. This involved combining deep features extracted using **ResNet50** with handcrafted **RGB Color Histogram** and **Local Binary Pattern (LBP)** texture descriptors into a unified feature representation, followed by feature balancing and standardization to improve clustering performance.

---

## Note

This project was developed as part of a university group project for the **Computer Vision** course at Umm Al-Qura University.
