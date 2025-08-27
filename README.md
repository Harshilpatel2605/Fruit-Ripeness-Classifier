# Fruit Ripeness Classifier

A deep learning project to classify 3 fruits(Apple, Orange and Banana) based on their 3 ripeness stages: **Unripe, Fresh, and Rotten**. Built using **TensorFlow** and trained on a custom Kaggle dataset.

---

##  Features

- Classifies 3 types of fruits: Apples, Bananas, and Oranges.
- Detects 3 stages of ripeness: Unripe, Fresh, Rotten.
- Trained using GPU acceleration on Google Colab.
- Saves and loads the trained model for quick predictions.
- Includes confusion matrix visualization and accuracy plots.

---

##  Dataset

Dataset used: [Fruit Ripeness Dataset on Kaggle](https://www.kaggle.com/datasets/leftin/fruit-ripeness-unripe-ripe-and-rotten)  
- Organized into train/test folders.
- Nine classes:
  - Unripe: `unripe apple`, `unripe banana`, `unripe orange`
  - Fresh: `freshapples`, `freshbanana`, `freshoranges`
  - Rotten: `rottenapples`, `rottenbanana`, `rottenoranges`

---

##  Requirements

- Python 3.8+
- TensorFlow
- Matplotlib
- Kaggle API (for downloading dataset)

---

##  Usage

1. Clone the repo:
   ```bash
   git clone <repo_url>
   cd fruit-ripeness-classifier
   
