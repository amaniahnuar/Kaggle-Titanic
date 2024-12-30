# Kaggle Titanic Project  

This is my solution to the Kaggle competition **"Titanic: Machine Learning from Disaster"**, implemented in an IPython Notebook. The project demonstrates a practical approach to analyzing data, building predictive models, and submitting results to Kaggle. It's perfect for beginners exploring data science or Python-based machine learning competitions.  

[**View Static Version**](http://nbviewer.ipython.org/urls/raw.github.com/agconti/kaggle-titanic/master/Titanic.ipynb)  

---

## Installation  

Follow these steps to run this notebook interactively:  

1. Clone or download this repository.  
2. Install [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html).  
3. Navigate to the project directory and create a virtual environment:  
   ```bash  
   virtualenv env  
   ```  
4. Activate the virtual environment:  
   - **Linux/Mac:**  
     ```bash  
     source env/bin/activate  
     ```  
   - **Windows:**  
     ```bash  
     env\Scripts\activate  
     ```  
5. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
6. Start the Jupyter Notebook server:  
   ```bash  
   ipython notebook  
   ```  
7. Open `Titanic.ipynb` from the notebook dashboard to explore the analysis.  
8. When done, deactivate the virtual environment:  
   ```bash  
   deactivate  
   ```  

---

## Dependencies  

This project uses the following Python libraries:  
- [NumPy](http://www.numpy.org/)  
- [IPython](http://ipython.org/)  
- [Pandas](http://pandas.pydata.org/)  
- [SciKit-Learn](http://scikit-learn.org/stable/)  
- [SciPy](http://www.scipy.org/)  
- [StatsModels](http://statsmodels.sourceforge.net/)  
- [Patsy](http://patsy.readthedocs.org/en/latest/)  
- [Matplotlib](http://matplotlib.org/)  

---

## About the Kaggle Competition  

The **Titanic: Machine Learning from Disaster** competition challenges participants to predict which passengers survived the tragic sinking of the Titanic. This competition serves as an introduction to machine learning and provides a chance to work on a real dataset.  

**Background:**  
- The Titanic sank on April 15, 1912, after hitting an iceberg, claiming 1,502 lives out of 2,224 passengers and crew.  
- Survival rates varied significantly based on factors like gender, age, and class.  

**Goal:**  
Use machine learning to predict which passengers survived the disaster.  

Learn more on the [competition homepage](http://www.kaggle.com/c/titanic-gettingStarted).  

---

## Project Goals  

This notebook provides a practical example of data analysis with Python using the Titanic dataset. It’s designed for:  
- **Beginners** looking to learn data science and machine learning.  
- **Practitioners** seeking an example of Python-based exploratory analysis and predictive modeling.  

---

## Features  

### Data Handling  
- Importing and cleaning data with Pandas.  
- Visualizing data with Matplotlib.  

### Data Analysis  
- Supervised machine learning techniques:  
  - Logistic Regression  
  - Support Vector Machines (SVM) with different kernels  
  - Random Forest  
- Visualization and interpretation of results.  

### Validation  
- K-fold cross-validation for model evaluation.  
- Exporting predictions for submission to Kaggle.  

---

## Benchmark Scripts  

Simple benchmark scripts are available in the "Python Examples" folder. These scripts are based on the originals by Astro Dave and have been simplified for easier understanding by beginners.  

[Competition Website](http://www.kaggle.com/c/titanic-gettingStarted)  


