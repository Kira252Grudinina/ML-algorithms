# ML Algorithms From Scratch

Machine learning algorithms implemented from scratch using NumPy, with detailed explanations and real-world datasets.

> 📚 Part of my Medium series: **"From Intuition to Math to Code"**

## Goal

Understanding ML by building algorithms without black-box libraries (scikit-learn used only for validation).

---

## Contents

### [01 - Linear Regression](./01-linear-regression/)

**Predicting Spotify Song Popularity**

-  [Article 1: Theory](https://medium.com/@grudinina.kira/linear-regression-from-intuition-to-math-to-code-56a1e4d6d916) - Intuition → Math → Code
-  [Article 2: Practice](https://medium.com/@grudinina.kira/linear-regression-in-practice-predicting-spotify-song-popularity-81b9b76188e6) - Real data, feature scaling, evaluation
-  Dataset: 114,000 Spotify tracks
-  Concepts: Gradient descent, feature scaling, data leakage prevention

- **Main Learning:** Feature scaling prevents gradient explosion 

---

### 02 - Logistic Regression
Coming soon!
---
## Quick Start

```bash
# Clone repository
git clone https://github.com/Kira252Grudinina/ML-algorithms
cd ML-algorithms
# Create virtual environment
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Add kernel to Jupyter
python -m ipykernel install --user --name=ml-algos --display-name "Python (ML-Algos)"

# Run notebook
cd 01-linear-regression
jupyter notebook linear_regression_spotify_final.ipynb
```

**In Jupyter:** Select kernel **"Python (ML-Algos)"** from Kernel → Change Kernel
---

## 📋 Requirements

- Python 3.8+
- NumPy, Pandas, Matplotlib, Seaborn
- scikit-learn (for validation only)
- Jupyter Notebook
- kagglehub (for dataset download)

See [requirements.txt](requirements.txt) for full list.

---

## 👩‍💻 Author

**Kira Grudinina**

- Medium: [@grudinina-kira](https://medium.com/@grudinina.kira)
- LinkedIn: [Kira Grudinina](https://www.linkedin.com/in/kiragrudinina/)
- GitHub: [Kira252Grudinina](https://github.com/Kira252Grudinina)

---

## 📄 License

MIT License - feel free to use for learning!

---

## 🤝 Contributing

Found a bug or want to add an algorithm? Open an issue or PR!

