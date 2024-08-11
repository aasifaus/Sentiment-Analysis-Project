# Sentiment Analysis Project

## Overview
This project is part of the ISY503 course and focuses on building a sentiment analysis tool using Natural Language Processing (NLP) techniques. The tool classifies text reviews as positive or negative, providing valuable insights for understanding customer sentiment.

## Project Structure
- **app.py**: Main application script that runs the Flask web server and handles sentiment analysis predictions.
- **Model_Training.ipynb**: Jupyter notebook for training the sentiment analysis model, including data preprocessing, model architecture, and evaluation.
- **ReviewToCSV.py**: Script for converting raw reviews into a structured CSV format for model training.
- **index.html**: Front-end of the web application where users can input text and receive sentiment predictions.
- **sentiment_model.h5**: Trained model file saved after the training process.
- **positive.review** & **negative.review**: Raw review files used for training the model.

## Installation

### 1. Clone the Repository
First, clone this repository to your local machine using Git:

```bash
git clone https://github.com/yourusername/sentiment-analysis-project.git
cd sentiment-analysis-project

2. Create a Virtual Environment (Optional but Recommended)
It's recommended to use a virtual environment to manage dependencies:

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

3. Install Dependencies
Install the required Python packages using pip:

pip install -r requirements.txt

4. Run the Web Application
Start the Flask web server to run the web application:

python app.py

The application will be accessible at http://localhost:5000
