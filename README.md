# Sentiment Analysis Emoji Mood Classifier

This Python script utilizes the [TextBlob](https://textblob.readthedocs.io/en/dev/) library to perform sentiment analysis on input text and categorize it into positive, negative, or neutral moods. The mood is represented by an emoji and a sentiment score, encapsulated within a convenient data class.

## Features

- **Sentiment Analysis:** The script leverages TextBlob to analyze the sentiment of the input text, providing a polarity score that indicates whether the text is positive, negative, or neutral.

- **Mood Categorization:** The sentiment score is used to categorize the mood into three classes: 😊 Good (positive), 😠 Unhappy (negative), and 😐 Neutral.

- **Threshold Customization:** Users can customize the threshold for mood classification by adjusting the `threshold` parameter, allowing for fine-tuning based on specific use cases.

- **Continuous User Interaction:** The script includes a loop for continuous user interaction, making it easy to input various texts and receive real-time mood feedback.

## Usage

1. Clone the repository:
```bash
https://github.com/avirooppal/Sentiment-Analysis.git
```
2. Navigate to the project directory:

```base
cd sentiment-analysis-mood-classifier
```
3.Run the script:
```bash
app.py
```
4.Enter text when prompted, and observe the mood classification along with the sentiment score.

Feel free to use and modify this script for sentiment analysis in your projects!

## Requirements
Python 3.x
TextBlob library (install via pip install textblob)
