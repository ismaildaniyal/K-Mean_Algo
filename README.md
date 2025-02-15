# K-Means Clustering: From Scratch vs Scikit-Learn

## Overview
This project implements the **K-Means clustering algorithm** from scratch without using any external libraries. Additionally, the same algorithm is implemented using **Scikit-Learn's KMeans** module. Both implementations are then compared on the **Iris dataset** to analyze performance, accuracy, and computational efficiency.

## Features
- **K-Means from Scratch:** Implements the K-Means clustering algorithm manually using Python.
- **Scikit-Learn K-Means:** Uses the `sklearn.cluster.KMeans` for clustering.
- **Comparison & Analysis:** Compares clustering results, performance, and accuracy between the two implementations.

## Dataset
- The **Iris dataset** is used for clustering.
- It contains 150 samples with 4 features each, categorized into 3 clusters.

## Files
- `k_mean.ipynb` - Jupyter Notebook implementing K-Means from scratch and using Scikit-Learn.
- `Iris_no_species.csv` - Dataset used for clustering (without labels).
- `archive/Iris.csv` - Original Iris dataset.
- `archive/database.sqlite` - Additional database file (if applicable).
- `cp.ipynb` - Additional computations and analysis.

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install numpy pandas matplotlib scikit-learn
```

### Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/ismaildaniyal/K-Mean_Algo.git
   cd K-Mean_Algo
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook k_mean.ipynb
   ```
3. Run the notebook cells to execute and compare both implementations.

## Comparison Criteria
- **Cluster Assignments:** Check how both implementations categorize the data.
- **Centroid Initialization:** Evaluate centroid positioning in both methods.
- **Computational Efficiency:** Measure execution time and complexity.
- **Accuracy & Convergence:** Analyze how quickly and accurately clusters form.

## Results & Findings
- The **manual implementation** provides deeper insights into K-Means working principles.
- The **Scikit-Learn implementation** is significantly faster due to optimized computations.
- Performance and clustering results are similar, but Scikit-Learn is more efficient for large datasets.

## Future Enhancements
- Implement **K-Means++** for better centroid initialization.
- Optimize the manual implementation for improved performance.
- Extend the comparison to other clustering algorithms.

## Author
**Ismail Daniyal**

## License
This project is licensed under the MIT License.

---
Feel free to contribute by improving the implementation or extending the comparison!
