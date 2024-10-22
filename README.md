# MatteMaster-Advanced Image Background Removal

This project involves the development of a Chrome extension designed to detect fake news in Indian media. Using machine learning models trained on a dataset of Indian news articles, the extension predicts the authenticity of news content in real time, providing users with an effective tool to combat misinformation.

## Overview

The project compares two different machine learning models: a Decision Tree Classifier and an LSTM (Long Short-Term Memory) neural network. Both models are designed to analyze the textual content of news articles and classify them as either real or fake. The extension is built using Python, TensorFlow, NLP, and Flask, offering a seamless, user-friendly experience for real-time news authentication.

## Features

- **Real-time Fake News Detection:** The extension analyzes news articles in real time, providing immediate feedback on their authenticity.
- **Dual Model Approach:** Users can compare the performance of a Decision Tree Classifier and an LSTM model for detecting fake news.
- **User-Friendly Interface:** The extension is integrated into a Chrome browser for easy and convenient use.
- **NLP and Machine Learning:** Leverages natural language processing (NLP) and machine learning models to analyze and classify news content.

## Results

| Model                     | Accuracy  |
|----------------------------|-----------|
| Decision Tree Classifier    | 85%       |
| LSTM Model                  | 92%       |

The **LSTM model** demonstrates higher accuracy due to its ability to understand the context of the text, making it better suited for predicting the authenticity of news articles. On the other hand, the **Decision Tree Classifier** offers a faster but slightly less accurate approach, providing an interpretable decision-making process.

![Screenshot (103)](https://github.com/user-attachments/assets/00693ad3-03d5-44d0-9334-ec0b3f149874)
![Screenshot (104)](https://github.com/user-attachments/assets/8d2d5203-3349-495e-9fcd-88a128a1f873)
![Screenshot 2024-04-11 025035](https://github.com/user-attachments/assets/dfef8d9f-15ee-4966-928e-89f1268cd402)

## Technology Stack

- Python 3.x
- TensorFlow 2.x
- Flask
- Chrome Browser

## Dataset

The models are trained using the Fake-Real News Dataset, which contains a large collection of Indian news articles labeled as either "real" or "fake." The dataset can be found [here](https://github.com/laxmimerit/fake-real-news-dataset).

## References
- Fake-Real News Dataset: [Dataset Repository](https://github.com/laxmimerit/fake-real-news-dataset).
- LSTM Paper: Hochreiter, Sepp, and Jürgen Schmidhuber. "Long short-term memory." Neural computation 9.8 (1997): 1735-1780.
