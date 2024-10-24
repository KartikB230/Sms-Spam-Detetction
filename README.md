Spam-Ham Classification with Comparative Model Analysis
This project classifies messages as either spam or ham using Natural Language Processing (NLP) techniques and machine learning models. It includes data visualization, preprocessing, and comparative analysis using three models: Naive Bayes, Support Vector Machine (SVM), and Random Forest.

Table of Contents
Installation
How to Run the Project
How to Insert the Dataset
Comparative Analysis of Models
Output
GitHub Repository
License
Installation
To run this project, you need to install the required libraries. These can be installed directly in Google Colab or your local environment. Use the following commands to install the libraries:

bash
Copy code
pip install nltk
pip install scikit-learn
How to Run the Project
Follow these steps to run the Jupyter notebook in Google Colab:

1. Open the Notebook in Google Colab
Option 1: Directly from GitHub
Go to Google Colab.
Click on the File menu and select Open Notebook.
In the pop-up window, go to the GitHub tab.
Enter the URL of this repository and select the .ipynb file.
Option 2: Manually Upload the Notebook
Download the .ipynb file from this repository.
In Colab, select File > Upload Notebook and upload the downloaded file.
2. Run the Notebook
Once the notebook is open in Colab, click on the Runtime tab.
Select Run All to execute all cells sequentially. Ensure you upload the dataset (instructions below).
How to Insert the Dataset
You can insert the dataset in two ways:

1. Upload the Dataset Locally
In the Colab interface, click on the Files icon on the left panel.
Click the Upload button and upload your dataset file (e.g., spam_ham_dataset.csv).
Modify the dataset path in the notebook code:
python
Copy code
df = pd.read_csv('/content/spam_ham_dataset.csv')
2. Load Dataset from Google Drive
Mount your Google Drive in Colab using the following code:

python
Copy code
from google.colab import drive
drive.mount('/content/drive')
dataset_path = '/content/drive/MyDrive/spam_ham_dataset.csv'
df = pd.read_csv(dataset_path)
Replace the dataset_path with the correct path to your file in Google Drive.

Comparative Analysis of Models
This project uses three machine learning models to classify the messages:

Naive Bayes
Support Vector Machine (SVM)
Random Forest
Each model is trained on the preprocessed text data, and their performance is compared based on accuracy, confusion matrix, precision, recall, and F1-score.

Output
The final section of the notebook provides:

Visualizations for data distribution and model comparison.
Model Performance Metrics:
Accuracy
Precision-Recall
Confusion Matrix for each model.
Comparative Analysis of Naive Bayes, SVM, and Random Forest.
GitHub Repository
You can find the project files and the Jupyter Notebook in this repository:
[Your GitHub Repository Link Here]

License
This project is licensed under the MIT License - see the LICENSE file for details.
