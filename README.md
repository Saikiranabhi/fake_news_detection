# Fake News Detection

A web application that detects whether a news article is **Fake** or **Real** using a machine learning model. Enter any news article text and instantly get a prediction!

---

## 🚀 Live Demo

You can deploy this app for free using [Streamlit Community Cloud](https://share.streamlit.io/):

1. Fork or clone this repository to your GitHub account.
2. Go to [share.streamlit.io](https://share.streamlit.io/) and sign in with GitHub.
3. Click **Create app**, select your repo, and set the main file as `app.py`.
4. Click **Deploy**. Your app will be live in minutes!

---

## 🛠️ Technologies Used

- **Python**: Main programming language for data processing and model building.
- **Streamlit**: Framework for building interactive web apps quickly and easily in Python.
- **scikit-learn**: Used for machine learning, including text vectorization and logistic regression.
- **pandas**: For data manipulation and analysis.
- **joblib**: For saving and loading the trained model and vectorizer efficiently.

### Technology Descriptions
- **Streamlit**: Allows you to create beautiful web apps for data science and ML with minimal code.
- **scikit-learn**: Popular ML library for Python, used here for text feature extraction and classification.
- **joblib**: Efficient serialization of large numpy arrays and models.

---

## 📁 Project Structure

```
Fake_news_detection/
├── app.py                  # Streamlit web app for fake news detection
├── Fake_news_detection.ipynb # Jupyter notebook for data analysis, preprocessing, and model training
├── Fake.csv                # Dataset of fake news articles
├── True.csv                # Dataset of real news articles
├── lr_model.jb             # Trained Logistic Regression model (joblib format)
├── vectorizer.jb           # Trained TF-IDF vectorizer (joblib format)
├── read.txt                # Setup and deployment instructions
```

---

## 📖 How it Works

1. **Data Preparation**: News articles are loaded from `Fake.csv` and `True.csv`.
2. **Preprocessing**: Text is cleaned and vectorized using TF-IDF.
3. **Model Training**: A Logistic Regression model is trained to classify news as fake or real.
4. **Web App**: The trained model and vectorizer are loaded in `app.py`. Users input news text, and the app predicts its authenticity.

---

## 📚 Usage

- **Local**:  
  1. Install dependencies: `pip install -r requirements.txt`  
  2. Run: `streamlit run app.py`
- **Online**: See [Live Demo](#-live-demo) above.

---

## 🔗 GitHub Repository

[https://github.com/yourusername/Fake_news_detection](https://github.com/yourusername/Fake_news_detection)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License. 