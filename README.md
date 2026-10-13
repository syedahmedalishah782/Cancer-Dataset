Cancer Classification Using Logistic Regression

 Project Overview
This project uses Machine Learning and Logistic Regression to classify cancer dataset records based on numerical features. It includes model training, evaluation, and interactive prediction interfaces using Gradio and Flask.

 Dataset
The project uses `Cancer_Data.csv`.

- **B:** Benign
- **M:** Malignant

The diagnosis labels are converted into numerical values for model training: B = 0 and M = 1.

 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Logistic Regression
- Gradio
- Flask

 Project Features
- Data preprocessing and cleaning
- Training and testing the Logistic Regression model
- Feature scaling using StandardScaler
- Model evaluation using accuracy, classification report, ROC-AUC, and confusion matrix
- Interactive prediction interface using Gradio
- Web-based prediction interface using Flask

 How to Run
1. Download or clone this repository.
2. Open `Cancer_Logistic_Regression_Gradio_Flask.ipynb` in Google Colab or Jupyter Notebook.
3. Install the required libraries.
4. Upload `Cancer_Data.csv` when prompted.
5. Run the notebook cells in order.
6. Follow the notebook instructions to launch the Gradio and Flask interfaces.

 Files Included
- `Cancer_Logistic_Regression_Gradio_Flask.ipynb` — complete project code
- `Cancer_Data.csv` — dataset
- `README.md` — project documentation

 Purpose
This project was developed for university Machine Learning coursework to practice classification, model evaluation, and web interface development.

## Disclaimer
This project is for educational purposes only. Its predictions are not medical diagnoses and must not be used to make healthcare decisions.
