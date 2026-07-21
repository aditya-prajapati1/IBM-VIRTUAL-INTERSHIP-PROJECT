# 📰 Fake News Detection using Machine Learning

A machine learning project that classifies news articles as **Real** or **Fake** using Natural Language Processing (NLP) and multiple classification algorithms. The project performs text preprocessing, converts text into numerical features using **TF-IDF Vectorization**, trains different ML models, and compares their performance.

---

## 📌 Features

- Data preprocessing and text cleaning
- Fake and real news classification
- TF-IDF feature extraction
- Multiple machine learning models
- Model performance comparison
- Manual testing with custom news articles

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - Pandas
  - NumPy
  - Scikit-learn
  - Regular Expressions (re)
  - Jupyter Notebook

---

## 📂 Dataset

The project uses two CSV files:

- `True.csv`
- `Fake.csv`

Each dataset contains news articles labeled as:

- **1 → Real News**
- **0 → Fake News**

---

## 🔄 Project Workflow

1. Load Fake and True news datasets
2. Assign labels to each dataset
3. Merge both datasets
4. Shuffle the data
5. Remove unnecessary columns:
   - Title
   - Subject
   - Date
6. Clean text by:
   - Converting to lowercase
   - Removing URLs
   - Removing punctuation
   - Removing numbers
   - Removing newline characters
7. Split data into training and testing sets
8. Convert text into TF-IDF vectors
9. Train multiple machine learning models
10. Evaluate and compare model performance
11. Predict whether custom news is Real or Fake

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📁 Project Structure

```
Fake-News-Detection/
│
├── Fake_News_Detection.ipynb
├── Fake.csv
├── True.csv
├── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Fake-News-Detection.git
```

Move into the project folder:

```bash
cd Fake-News-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Fake_News_Detection.ipynb
```

---

## ▶️ How to Run

1. Place `Fake.csv` and `True.csv` in the project directory.
2. Run all notebook cells in order.
3. Train the models.
4. Test the models using the provided evaluation metrics.
5. Enter your own news article for manual prediction.

---

## 📦 Requirements

Create a `requirements.txt` file with:

```text
numpy
pandas
scikit-learn
jupyter
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 📈 Future Improvements

- Use advanced text preprocessing (stemming/lemmatization)
- Hyperparameter tuning
- Cross-validation
- Deploy the model using Streamlit or Flask
- Support live news article prediction from URLs
- Experiment with transformer-based models such as BERT

---

## 🎯 Learning Outcomes

This project demonstrates:

- NLP preprocessing techniques
- TF-IDF Vectorization
- Text classification
- Training and evaluating multiple ML models
- Binary classification using Scikit-learn
- Manual prediction on unseen text

---

## 👨‍💻 Author

**Aditya Prajapati**

B.Tech – Computer Science & Engineering (AI & ML)
Batch - 4

---

## ⭐ If you found this project useful, consider giving it a star!
