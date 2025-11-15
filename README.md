# Unsupervised-Machine-Learning

## DBSCAN Clustering on Iris Dataset

The **DBSCAN clustering algorithm** was applied to the **Iris dataset** to identify clusters based on point density. The algorithm found **2 clusters**, with **34 points** marked as **noise**. 

The **Silhouette Score** of `0.36` indicates a relatively weak clustering, suggesting that there is room for improvement in the **clustering parameters** (`eps` and `min_samples`). 

The results were visualized using **PCA** (Principal Component Analysis) to reduce the data to 2D. The 2D plot clearly shows how the algorithm grouped the data into two distinct clusters while marking noise points that did not fit well into either cluster.

## Requirements

- Python 3.x
- scikit-learn
- pandas
- matplotlib
- numpy

## How to Run

1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
