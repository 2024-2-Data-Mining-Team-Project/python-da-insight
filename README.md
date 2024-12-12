# python-de-insight

## Implementation

### PCA Execution
1. **Objective**: Reduce the dimensionality of high-dimensional data while retaining key information for effective recommendations.
2. Used the average of yearly features to minimize data sparseness and computational complexity.
3. Applied PCA to derive new principal components, replacing the original features with linear combinations of the most informative ones.

### Results of PCA
- PCA produced new features through linear combinations of the original data.
- The analysis highlighted the most impactful variables shaping commercial districts.
- However, the transformation resulted in a loss of interpretability for the original features.

### Outcome
- Due to the interpretability issues of PCA-transformed features, the approach was not directly utilized in the recommendation system.
- Instead, key features like rental prices and population density were selected manually, as these factors are critical for decision-making in business startups.

