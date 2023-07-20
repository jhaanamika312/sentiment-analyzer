# Final-tasks
# **SENTIMENT MODEL**

## Use of the webpage
It takes sentence as the input from user and predict the sentiment as the output. To determine sentiment following libraries are used:
Flask
Sklearn
Vader Sentiment
NLTK

### VADER Sentiment
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media, and works well on texts from other domains.

## File of the repo
The app.py file is a flask webserver that host the sentiment analysis model 
The requirement.txt file has the necessary libraries and requirements need to run the code
The dockercompose.yml file is to build docker image and run the container

## How to run it
1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd sentiment-analyzer

2. pip install -r requirements.txt

3. ### Using Docker
   docker build -t sentiment-analyzer .
   docker run -p 5000:5000 sentiment-analyzer

4. Access the app in your browser at http://localhost:5000/

## Dependencies
Python 3.10
Flask
scikit-learn
vaderSentiment
nltk




## Output
Output of the code in mp4 format is included in the folder 'output'
