# Ancient Indus Valley Script Clustering

![Indus Valley Civilization](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQJFZXePBN4Wrwz4_4MgwaGcA2fHfPijg7A8A&s)

---

## Overview
This project explores the ancient Indus Valley Civilization script using advanced machine learning techniques. By leveraging deep learning for feature extraction and K-means clustering for unsupervised learning, we aim to uncover hidden patterns and insights in the undeciphered Indus script.

---

## Objectives
1. Extract features from images of ancient Indus script seals using the VGG16 model.
2. Reduce dimensionality with PCA for effective clustering visualization.
3. Apply K-means clustering to group similar script images and identify potential patterns.

---

## Tools and Technologies
- **Deep Learning Model**: VGG16 (Pretrained on ImageNet)
- **Unsupervised Learning**: K-means Clustering
- **Dimensionality Reduction**: Principal Component Analysis (PCA)
- **Libraries**: TensorFlow, NumPy, Matplotlib, Scikit-learn, Pandas

---

## Dataset
**Kaggle Dataset**: [IM-417-150: Indus Valley Script Dataset](https://www.kaggle.com/datasets/storesource/im-417-150)

- **Source**: Extracted from images of seals belonging to the Indus Valley Civilization.
- **Original Compilation**:
  - "The Indus Scripts: Texts, Concordance and Tables" (1977) by Iravatham Mahadevan.
  - Published by Archaeological Survey of India.

**Special Thanks**:
- To Iravatham Mahadevan for compiling "The Indus Scripts: Texts, Concordance and Tables."

---

## Workflow
1. **Data Preprocessing**:
   - Normalize and preprocess images.
   - Augment dataset for model robustness.

2. **Feature Extraction**:
   - Use VGG16 to extract deep features from images.

3. **Dimensionality Reduction**:
   - Apply PCA to reduce high-dimensional features to two dimensions.

4. **Clustering**:
   - Perform K-means clustering on reduced features.
   - Visualize clusters to interpret patterns.

5. **Evaluation**:
   - Assess cluster quality using visual analysis and inertia scores.

---

## Results
- **Clusters**: Grouped images of the script into visually similar patterns.
- **Insights**: Highlighted potential relationships between symbols based on cluster distributions.
- **Visualization**: PCA-reduced features plotted with K-means cluster labels.

---

## How to Run
1. Install dependencies from the `requirements.txt` file.
2. Place the dataset in the appropriate folder structure.
3. Execute the Jupyter notebook `Project_Indus_Script_Clustering.ipynb` to train and visualize results.

---

## Future Scope
- Deciphering potential meanings using additional clustering and sequence prediction.
- Exploring other unsupervised techniques like DBSCAN for denser cluster detection.
- Collaborating with archaeologists to validate findings.

---

## Acknowledgments
We extend our gratitude to:
- **Iravatham Mahadevan** for the original compilation of the Indus scripts.
- **Archaeological Survey of India** for preserving these invaluable records.

---

> "Unraveling the mysteries of the ancient world with the power of modern technology."

