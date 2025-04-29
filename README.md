# DS6050-Final-Project
Repo for basketball modeling final project.

# Predicting NBA Games Using Deep Learning

This project explores the use of deep learning models to predict NBA game outcomes using only pre-game team-level statistics. We evaluate logistic regression, random forest, stacking, XGBoost, a feedforward neural network, and a Transformer, comparing them across accuracy, precision, recall, F1-score, and AUC.

---

## Project Summary

- **Goal**: Predict win/loss outcomes using structured NBA data from Kaggle (2019–2024)
- **Models**: Logistic Regression, Random Forest, Stacking, XGBoost, Neural Network, Transformer
- **Best Model (Accuracy)**: Tuned Neural Network (62.1%)
- **Best Model (AUC)**: Tuned Transformer (0.552)
- **Key Techniques**: Rolling averages, matchups, contextual features, keras-tuner optimization

---

## Project Files

```text
DS6100 Final Code Update.ipynb   # Full pipeline: data prep, modeling, tuning, evaluation
final_paper.pdf
README.md
requirements.txt
```

---

## Downloads (Large Files)

All files are hosted externally due to GitHub's 25MB file limit. Some are available directly in the repo but all are available here for posterity.

- [Relevant files](https://drive.google.com/drive/folders/1iR8G5DNYTqL-EKp-sLve89Y1xEkXbjPz?usp=sharing)

To run evaluation locally, place the `.h5` model files in a `models/` directory and use the tuner data in `keras_tuner_dir/`.

---

## Setup Instructions
```bash
## (Optional) Create a virtual environment
python -m venv nba-env
source nba-env/bin/activate

## Install dependencies
pip install -r requirements.txt
```

## Final Report
The full academic paper is available in final_paper.tex, including:

- Abstract
- Motivation
- Methodology
- Experiments
- Results
- Conclusion
- Contributions

## Author
Devlin Bridges

University of Virginia – School of Data Science
Email: cbv6gd@virginia.edu

## License

This project is released under the MIT License.

## Citation

If you reference this project in your own work, please cite:

Devlin Bridges. Predicting NBA Games Using Deep Learning. University of Virginia, DS6050 (2025).
