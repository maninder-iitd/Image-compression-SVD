# Image-compression-SVD
Singular Value Decomposition factorizes the matrix into three components:   \[   A = U \Sigma V^T   \] - By keeping only the largest singular values, we obtain a **low-rank approximation** of the original image.
# Image Compression Using Singular Value Decomposition (SVD)

## 📌 Overview
This project demonstrates image compression using Singular Value Decomposition (SVD). Each RGB channel of the image is treated as a matrix and approximated using a reduced number of singular values to achieve compression with minimal loss of visual quality.

## 🔧 Technologies Used
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## 📊 Method
- RGB channel decomposition
- SVD-based low-rank approximation
- Image reconstruction using top-k singular values

## 📈 Results
The results show that even with a small number of singular values, the reconstructed image maintains most of the original visual features.

## 🚀 How to Run
1. Clone the repository
2. Open the Jupyter notebook
3. Run all cells

## 📚 Learning Outcome
- Practical understanding of SVD
- Application of linear algebra in image processing
- Matrix approximation and compression techniques
