# Mithya: Fake News Detection Application

![Mithya: Fake News Detection](fake_news_detection.png)

Welcome to Mithya, the Fake News Detection App created by Vikas Jain! This repository houses a powerful machine learning-based web application that specializes in identifying fake news articles using advanced classification models, including Passive Aggressive Classifier and LSTM (Long Short-Term Memory).

## Overview

In this age of information overload, fake news has become a significant concern. Mithya was developed to tackle this issue by offering an intuitive and robust app capable of accurately distinguishing between fake and genuine news articles. Leveraging cutting-edge machine learning algorithms, Mithya provides users with a user-friendly interface for seamless interaction.

## Features

- **Multiple Classification Models**: Mithya employs two state-of-the-art classifiers, the Passive Aggressive Classifier and LSTM, to achieve superior detection accuracy.

- **Custom Text Input**: Users have the convenience of entering article text directly into the app for immediate analysis.

- **URL Support**: Mithya also supports analyzing news articles through URL input, saving users time and effort.

- **Confidence Level**: The classification results include a confidence level to indicate the model's certainty in its prediction.

- **Visualizations**: Informative visualizations illustrate model performance, facilitating a better understanding of the results.

## How to Use

1. Clone this repository to your local machine.

2. Install the required dependencies by running `pip install -r requirements.txt`.

3. Launch the app by executing `python app.py`.

4. Access the app through your web browser at `http://localhost:5000`.

5. Enter the article text directly or provide a URL for analysis.

6. Click the "Detect" button to view the results, including whether the news is fake or genuine and the confidence level.

## Dataset

The models in Mithya have been trained on a diverse dataset consisting of labeled fake and genuine news articles. While the dataset itself is not included in this repository due to its size, you can obtain it from [source link] or use your custom dataset for retraining.

## Model Performance

Both the Passive Aggressive Classifier and LSTM models have undergone rigorous training and evaluation. You can find detailed accuracy, precision, recall, and F1-score metrics in the [model_metrics.md](model_metrics.md) file.

## Contributions

Contributions to enhance Mithya's functionality, add new features, or improve classification models are highly appreciated. Please feel free to open an issue or submit a pull request.

## Disclaimer

Mithya is designed to identify fake news based on available data and trained models. While it strives for accuracy, it may not be foolproof. Users are encouraged to exercise critical thinking and verify information from multiple sources.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use and modify the code for your own purposes.

Enjoy detecting fake news with Mithya!

**The Mithya Team**
