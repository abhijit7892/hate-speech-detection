# Hate-Speech-Detection
NLP model classifies hate speech using CountVectorizer + Decision Tree.
## Classification
Classifies tweets into 3 categories Hate Speech, Offensive language, Neither. 
# Library 
Python,Scikit-learn,NLTK,Numpy,Pandas,Matplotlib,Seaborn.
Machine learning tools- CountVectorizer, Decision Tree Classifier.
## Dataset
Size:24,783 labelled tweets.
Source:Kaggle dataset.
Splitting:70% Train(17,348) ,30% Test(7,435) with random state=42.
Classes:Hate Speech,Offensive language,Neither 
Features:Count  Vectors with 25,693 dimensions.
## Results
Accuracy:87%
F1-Score(Weighted):87%
## How to Run
1. Clone: https://github.com/abhijit7892/hate-speech-detection.git
2. Install: `pip install pandas numpy scikit-learn nltk matplotlib seaborn`
3. Run: Open hate-speech-detection.ipynb in VS Code.
