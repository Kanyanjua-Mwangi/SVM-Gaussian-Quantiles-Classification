# Support Vector Machines & Hyperparameter Tuning  
Gaussian Quantiles Classification

End-to-end demonstration of SVM classifiers using linear and RBF kernels on a synthetic non-linearly separable dataset.  
The project compares kernel performance, visualizes decision boundaries, and applies GridSearchCV for hyperparameter optimization.

## Project Highlights

- Dataset: Synthetic Gaussian quantiles (1000 samples, 4 features, binary classes)
- Models compared: Linear SVM vs RBF SVM
- Visualization: 2D decision boundaries showing linear vs curved separation
- Tuning: GridSearchCV over kernel, C, and gamma parameters
- Results:
  - Linear kernel: 45.67% accuracy (fails on non-linear data)
  - Default RBF kernel: 97.67% accuracy (excellent separation)
  - Tuned RBF: 92.33% accuracy (suboptimal due to limited grid)

## Repository Contents

- `svm_gaussian_quantiles.ipynb` – Main analysis notebook
- `requirements.txt` – Dependencies
- `README.md` – This file
- (Optional) `images/` – Decision boundary plots

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/svm-gaussian-quantiles-classification.git
   cd svm-gaussian-quantiles-classification
