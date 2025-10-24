# Fruit Classifier

The goal of this project is to build and evaluate machine learning models that classify fruits (apples, bananas, grapes) based on their features (color, size and weight).  
This task reflects a typical supervised classification problem: the model is trained on labeled data and then evaluated on its ability to classify new data. In this project two models, Logistic Regression and Decision Tree, will be compared using different performance metrics (accuracy, precision, recall, f1-score, ROC AUC).



## Project Structure
```
fruit-classifier/
├── notebooks/           # Jupyter notebook
├── data/               # Data files
├── requirements.txt    # Python dependencies
└── README.md   
```
## Setup

### Prerequisites
- Python 3.9+ installed
- pip installed

### Installation

1. Clone repository
```
git clone https://github.com/monbbemka/fruit-classifier.git
cd [project-directory]
```
2. Create and activate virtual environment
```
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

3. Install dependencies
```
pip install -r requirements.txt
```
4. Run in editor (e.g. vsCode) or launch in web
```
jupyter lab
```


