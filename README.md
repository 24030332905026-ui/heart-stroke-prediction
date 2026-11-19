# 🫀 Heart Stroke Risk Prediction Using Machine Learning

## 📌 About the Project

Heart Stroke Risk Prediction is a Machine Learning project developed to predict the possibility of stroke based on user-provided health-related information.

This project was developed in two major stages. First, I collected a dataset from Kaggle and used Jupyter Notebook to explore the data, implement multiple Machine Learning algorithms, train the models, and compare their performance.

After evaluating the models, the Decision Tree algorithm achieved the highest accuracy among the algorithms I tested. Therefore, I selected it as my final model.

In the second stage, I saved the trained model and other required files in `.pkl` format, then imported them into PyCharm. Using Python and the Streamlit library, I developed an interactive application that allows users to enter information and receive prediction results through a user-friendly interface.

## 🎯 Project Objectives

- Understand and analyze a real-world healthcare dataset.
- Apply data preprocessing and exploratory data analysis.
- Implement and train multiple Machine Learning algorithms.
- Compare model performance based on accuracy.
- Select the best-performing model.
- Save and reuse the trained model using Pickle files.
- Develop an interactive application using Streamlit.

## 📊 Dataset Collection

The dataset was collected from Kaggle.

**Dataset Source:** Kaggle

The dataset was used for data exploration, preprocessing, model training, and evaluation.

## 🧠 Phase 1: Model Development Using Jupyter Notebook

The first stage of the project was completed using Jupyter Notebook.

### Steps Followed:

**1. Dataset Collection**

- Downloaded the Heart Stroke Prediction dataset from Kaggle.
- Created a Machine Learning project folder in Jupyter Notebook.
- Loaded the dataset for further analysis.

**2. Library Importing**

- Imported the required Python libraries.
- Imported Machine Learning algorithms and supporting modules.

**3. Data Analysis and Preprocessing**

- Explored the dataset.
- Examined the available features.
- Prepared the data for Machine Learning model training.

**4. Model Training**

- Implemented multiple Machine Learning algorithms.
- Trained each algorithm using the prepared dataset.
- Evaluated and compared their prediction performance.

**5. Model Selection**

- Compared the accuracy of the trained algorithms.
- Decision Tree achieved the highest accuracy in my experiments.
- Selected Decision Tree as the final prediction model.

**6. Model Saving**
Saved the trained model and supporting components in Pickle (`.pkl`) format for future use in the application.

## 🏆 Final Selected Algorithm

### Decision Tree Classifier

The Decision Tree algorithm achieved the highest accuracy among the algorithms tested during this project.

It was selected as the final model for integration into the interactive application.

## 💻 Phase 2: Interactive Application Development Using PyCharm

After completing the model training process, I moved to PyCharm for application development.

### Steps Followed:

1. Opened the Machine Learning project in PyCharm.
2. Imported the saved `.pkl` model files.
3. Created the `app.py` Python file.
4. Integrated the trained Decision Tree model into the application.
5. Used the Streamlit library to develop the interactive interface.
6. Created input fields for users to enter the required information.
7. Connected the user inputs with the trained Machine Learning model.
8. Displayed the prediction results through the Streamlit application.

## ✨ Key Features

- Machine Learning-based prediction.
- Implementation of multiple ML algorithms.
- Model comparison and selection.
- Saved and reusable trained model.
- Interactive Streamlit user interface.
- User input-based prediction results.
- Python-based application development.

## 🛠️ Technologies and Tools Used

| Technology       | Purpose                             |
| ---------------- | ----------------------------------- |
| Python           | Programming language                |
| Kaggle           | Dataset collection                  |
| Jupyter Notebook | Model development and training      |
| Pandas           | Data manipulation                   |
| NumPy            | Numerical operations                |
| Matplotlib       | Data visualization                  |
| Seaborn          | Data visualization                  |
| Scikit-learn     | Machine Learning algorithms         |
| Pickle           | Saving trained model files          |
| PyCharm          | Application development             |
| Streamlit        | Interactive user interface          |
| Git & GitHub     | Version control and project hosting |

## 📁 Project Files

| File                                 | Description                                                   |
| ------------------------------------ | ------------------------------------------------------------- |
| `heart_stroke_risk_prediction.ipynb` | Jupyter Notebook containing ML experiments and model training |
| `app.py`                             | Streamlit application source code                             |
| `Decision_Tree_heart.pkl`            | Saved Decision Tree model                                     |
| `scaler.pkl`                         | Saved data scaler                                             |
| `columns.pkl`                        | Saved model column information                                |
| `heart`                              | Dataset file                                                  |

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/24030332905026-ui/heart-stroke-prediction.git
```

### Step 2: Open the Project

Open the downloaded project folder in PyCharm.

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn streamlit
```

### Step 4: Run the Streamlit Application

```bash
streamlit run app.py
```

### Step 5: Use the Application

- Open the application in your browser.
- Enter the required health-related information.
- Submit the information.
- View the prediction result.

## 📚 What I Learned

Through this project, I gained practical experience in:

- Collecting datasets from Kaggle.
- Working with Jupyter Notebook.
- Understanding and implementing Machine Learning algorithms.
- Training and comparing multiple ML models.
- Evaluating model performance.
- Saving and loading trained models using Pickle.
- Working with PyCharm.
- Building interactive applications using Streamlit.
- Integrating a trained Machine Learning model into a user interface.

## 👨‍💻 Developed By

**Jay Laxman Madhavi**

Computer Science and Engineering Student

This project represents my practical learning journey in Machine Learning, from dataset collection and model training to developing an interactive application.

## ⚠️ Disclaimer

This project is developed for educational purposes only. Its predictions are not medical diagnoses and should not be used as a substitute for professional medical advice.

---

⭐ Thank you for visiting my project repository!

**Learn • Experiment • Train • Build • Improve** 🚀
