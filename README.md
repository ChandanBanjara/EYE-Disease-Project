
# 🧠 Eye Disease Detection & Medical Recommendation System Using Deep Learning

This project is a deep learning-based system that detects eye diseases from retinal images and offers medical recommendations. It compares model performance with and without batch normalization and integrates a recommendation system based on prediction results.

## 📁 Project Structure
.
├── EYE_Disease_DL_Model.ipynb                 # Core model training for eye disease detection
├── Medical Recommendation System.ipynb        # Health recommendation logic based on predictions
├── using_batch_normalization.ipynb            # Model using batch normalization
├── without_using_batch_normalization.ipynb    # Model without batch normalization
├── .env                                       # Email and API key configuration (DO NOT SHARE)

## 🧰 Features

- CNN-based deep learning model for eye disease classification
- Performance comparison of batch normalization vs. without it
- Medical recommendations based on prediction outcomes
- Email notification system using SMTP
- OpenAI GPT integration (configured via `.env`)

## 🧪 Requirements

Install dependencies using:

bash
pip install -r requirements.txt

If not provided, here are typical dependencies:

txt
tensorflow
keras
numpy
matplotlib
seaborn
pandas
sklearn
opencv-python
email-validator
openai

## ⚙️ Configuration

Set the following in a `.env` file:

env
EMAIL_USER='your_email@example.com'
EMAIL_PASS='your_email_password_or_app_password'
EMAIL_FROM='your_email@example.com'

# OpenAI API key
export OPENAI_API_KEY='your_openai_api_key'

**Important:** Never share your `.env` file publicly, as it contains sensitive credentials.

## 🚀 How to Run

1. Launch **EYE_Disease_DL_Model.ipynb** to train the eye disease model.
2. Optionally compare **using_batch_normalization.ipynb** and **without_using_batch_normalization.ipynb**.
3. Use **Medical Recommendation System.ipynb** to generate medical advice based on predictions.
4. Make sure `.env` is properly configured for email and OpenAI features.

## 📊 Results

- The models were compared on training speed and accuracy.
- Batch normalization showed better generalization in most cases.
- The recommendation system improves user interaction post-prediction.

## 🔒 Security Note

Do **not** commit your `.env` file to public repositories. Always use `.gitignore`:

gitignore
.env

## 📫 Contact

For queries, reach out to:
- 📧 Chandanbanjara12@gmail.com
