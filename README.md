# Sms-Spam-Detetction

This project performs spam-ham classification using Natural Language Processing (NLP) and machine learning models such as Naive Bayes, SVM, and Random Forest. It includes data visualization, text preprocessing, and comparative analysis of model performance.

How to Run the Project in Google Colab
Step 1: Open the Notebook in Google Colab
Go to Google Colab.
Click on the File menu and choose Open Notebook.
In the pop-up window, go to the GitHub tab.
Enter the URL of this repository and select the .ipynb file from the list.
Alternatively, you can upload the notebook manually:
Download the .ipynb file from this repo.
In Colab, choose File > Upload Notebook and select the downloaded file.
Step 2: Insert the Dataset
After opening the notebook, scroll to the dataset loading section.
If you have the dataset file locally, upload it:
In Colab, click on the Files icon (left panel).
Click on the Upload button and choose your dataset (e.g., spam_ham_dataset.csv).
Modify the dataset path in the code accordingly.
Alternatively, you can mount your Google Drive and load the dataset directly from it:
python
Copy code
from google.colab import drive
drive.mount('/content/drive')
# Load the dataset from Google Drive
dataset_path = '/content/drive/MyDrive/your_dataset.csv'
df = pd.read_csv(dataset_path)
Step 3: Install Required Libraries
Ensure that you install the necessary libraries if not already present. Use the following commands in Colab cells:

python
Copy code
!pip install nltk
!pip install scikit-learn
Step 4: Run All Cells
Once the dataset is loaded and libraries are installed:

Click on Runtime in the menu.
Select Run All to execute all cells.
The notebook will run through data preprocessing, model training (Naive Bayes, SVM, Random Forest), and generate the comparative analysis of the models.
Output
The notebook includes model accuracy, confusion matrix, and precision-recall visualizations for performance comparison.

GitHub Link
[Your GitHub Repository Link Here]
