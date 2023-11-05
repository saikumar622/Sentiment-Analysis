# Sentiment-Analysis
We are using Amazon Alexa Reviews dataset (3150 reviews), that contains: customer reviews, rating out of 5, date of review, Alexa variant
First we generate sentiment labels: positive/negative, by marking positive for reviews with rating >3 and negative for remaining
Then, we clean dataset through Vectorization Feature Engineering (TF-IDF) - a popular technique
Post that, we use Support Vector Classifier for Model Fitting and check for model performance (we are getting >90% accuracy)
Last, we use our model to do predictions on real Amazon reviews using: a simple way and then a fancy way 

# Deployment

Steps to run on Windows
Prerequisites: Python 3.9 (ensure Python is added to PATH) + Git Client

Open GIT CMD >> navigate to working directory >> Clone this Github Repo 
Open Windows Powershell >> navigate to new working directory (cloned repo folder)

A)Create a virtual environment
   1.install virtual environment=pip install virtualenv
   
B)Create virtual environment by the name ENV
  1.virtualenv ENV
  
C)Activate ENV
  1..\ENV\Scripts\activate
  
D)Install project dependencies
  1.pip install -r .\requirements.txt

E)Run the project
  1.python app.py
![model-functionality](https://github.com/saikumar622/Sentiment-Analysis/assets/90022137/45c5f34e-f6e1-4627-8273-ca63d3fa0cc3)

 

