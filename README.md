# A system to scrape product’s feedback from website and classify them (bad or good) to suport customers in making choice ( buy or not)

Data was crawled from https://www.thegioididong.com/
Using 3 different models : RNN, SVM, NaiveBayes to classify and compare performance

For more details about training model, look at the notebook in 'Training' directory

# Front-end
## 1. Install package:
Run command at ./phone-recommendation-frontend: `yarn`

## 2. Disable CORS in Chrome:
Run command: `"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --disable-web-security --disable-gpu --user-data-dir=~/chromeTemp`

## 3. Run project:
Run command: `yarn dev`

# Back-end
## 1. Install python:
https://www.python.org/downloads/

## 2. Install flask:
`pip install Flask`

## 3. Run code:
`py main.py`
