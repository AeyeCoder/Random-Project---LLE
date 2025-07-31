# Random-Project---LLE
LLE and Random Projection used to convert 3D into 2D data. Check the difference
# Swiss Roll – Manifold Learning with Random Projection vs LLE

This project visualizes and compares the effectiveness of two dimensionality reduction techniques — **Random Projection** and **Locally Linear Embedding (LLE)** — on the classic Swiss Roll dataset.

## Objective

To unroll the 3D Swiss Roll into 2D using:
- **Gaussian Random Projection** (linear, unsupervised, fast)
- **Locally Linear Embedding (LLE)** (nonlinear, preserves local relationships)

## Techniques Used

### Gaussian Random Projection
- Projects data using a random Gaussian matrix.
- Preserves global structure approximately using the **Johnson-Lindenstrauss lemma**.
- Fast, but doesn’t consider the manifold structure.

### Locally Linear Embedding (LLE)
- Nonlinear method.
- Preserves **local neighborhoods** in lower dimensions.
- Successfully "unrolls" the Swiss Roll.

 #Dataset
- Used `sklearn.datasets.make_swiss_roll`
- 3D manifold embedded in 3D space.
