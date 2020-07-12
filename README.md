<h1>Machine Learning Web App (Classifier) - Mushrooms</h1>

<h2>Data set used</h2>

[Mushrooms dataset from UCI](https://archive.ics.uci.edu/ml/datasets/Mushroom)  
the mushrooms data set is in categorical data type  
<br/>
We will be having 3 different classification methods:

- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest

---

<h2>Setting Up</h2>
(use your preferred env)     
The below steps are for conda env

```
conda create --name mushrooms-ml-app python=3.6
```

```
conda activate mushrooms-ml-app
```

```
pip install -r requirements.txt
```

<h2>Running the app</h2>

```
streamlit run app.py
```

Open [http://localhost:8501/](http://localhost:8501/)
(default port)
