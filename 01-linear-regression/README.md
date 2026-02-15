# Linear Regression: Predicting Spotify Song Popularity

Implementation of Linear Regression from scratch to predict song popularity from audio features.

---

## 📝 Articles

**Part 1 - Theory:** [Linear Regression: From Intuition to Math to Code](https://medium.com/@grudinina.kira/linear-regression-from-intuition-to-math-to-code-56a1e4d6d916)
- Intuition behind linear relationships
- Mathematical derivation (gradient descent, MSE)
- Implementation from scratch with NumPy
- Tested on synthetic data (y = 3 + 2x + noise)

**Part 2 - Practice:** [Linear Regression in Practice: Predicting Spotify Song Popularity](https://medium.com/p/81b9b76188e6?postPublishedType=initial)
- Real messy data (114k Spotify tracks)
- Feature scaling (why it's critical!)
- Data leakage prevention
- Evaluation metrics (MSE, RMSE, R²)

---
## 📊 Dataset

**Spotify Tracks Dataset**
- 114,000 songs
- 9 audio features: danceability, energy, loudness, tempo, etc.
- Target: popularity (0-100)
- Source: [Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)

**Auto-downloads in notebook via:**
```python
import kagglehub
path = kagglehub.dataset_download("maharshipandya/-spotify-tracks-dataset")
```

---
The notebook includes:
- Complete EDA with visualizations
- Training without scaling (explosion demo)
- Training with scaling (success!)
- Comprehensive evaluation
- sklearn validation

---
## Files
```
01-linear-regression/
├── README.md                           # This file
├── linear_regression_spotify.ipynb     # Complete implementation
└── images/
    ├── convergence_comparison.png      # With vs without scaling
    ├── correlation_heatmap.png         # Feature correlations
    └── correlation_bar.png             # Feature-target relationships
```

---

