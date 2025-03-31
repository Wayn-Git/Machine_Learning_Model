# 📧 Email Spam Detector

A simple machine learning project to classify emails as spam or not spam.

## 🔍 Overview

This project uses machine learning techniques to detect spam emails. It's my first ML project, built with Python and various libraries.

## 🛠️ Technologies Used

- Python 3.9+
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy
- NLTK
- Matplotlib

## 🚀 Getting Started

### Prerequisites

```bash
pip install -r requirements.txt
```

### Running the Project

1. Clone this repository
2. Navigate to the project directory
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `spam_detector.ipynb`

## 📊 Project Structure

- `data/` - Contains email dataset
- `spam_detector.ipynb` - Main notebook with code and explanations
- `model/` - Saved trained model
- `requirements.txt` - Required packages

## ✨ Features

- Text preprocessing and cleaning
- Feature extraction using TF-IDF
- Training multiple classifiers (Naive Bayes, SVM, etc.)
- Model evaluation and comparison
- Visualization of results

## 📝 Results

The model achieves 97% accuracy on the test set. See the notebook for detailed metrics and visualizations.

## 🔮 Future Improvements

- Try more advanced NLP techniques
- Add a simple web interface
- Improve feature engineering
- Handle imbalanced datasets better

## 📚 Learning Resources

Resources that helped me during this project:
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Text Classification with NLTK](https://www.nltk.org/)

## 📄 License

MIT
