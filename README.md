# MEDICAL CHATBOT

## Requirements

Python 3.5 or newer.

Dependencies:

- Flask
- PyTorch
- NLTK
- NumPy
- Scikit-learn
- Pandas
- matplotlib

## Install requirements

Before running the application you need to install the dependencies. We recommend to use the virtual environment
[virtualenv](https://pypi.org/project/virtualenv/) for this.
Windows:

py -3 -m venv venv
venv\Scripts\activate
pip install flask torch nltk numpy==1.19.3 sklearn pandas matplotlib



In order for _nltk_ tokenization to work, the _'punkt'_ package must be downloaded. To do this, simply enter the Python shell and run the following:

python
import nltk
nltk.download('punkt')

This will install all the required dependencies needed to run the application successfully.

## Run

python -m flask run

