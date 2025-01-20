# Genetic Algorithm for Clustering

This project demonstrates the use of a Genetic Algorithm (GA) for clustering the Iris dataset. The GA is compared with the traditional K-means clustering algorithm to evaluate its performance using the Silhouette Score.

---

## Features

- **Genetic Algorithm (GA)**:
  - Uses crossover and mutation to evolve a population of clustering solutions.
  - Optimizes the Silhouette Score to find the best clustering solution.

- **Heuristic Initialization**:
  - Initializes the population with a heuristic seed to improve convergence.

- **K-means Clustering**:
  - Traditional K-means clustering is used as a baseline for comparison.

- **Visualization**:
  - Clustering results are visualized using scatter plots.

---

## Requirements

To run this code, you need the following Python libraries:

- `numpy`
- `scikit-learn`
- `matplotlib`

You can install the required libraries using:

```bash
pip install numpy scikit-learn matplotlib

---

## Example Output

### Genetic Algorithm Clustering
![GA Clustering](ga.png)

### K-means Clustering
![K-means Clustering](kmeans.png)
