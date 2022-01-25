# A Notebook showing the use of joblib to save trained Machine Learning models

After loading the data and performing exploratory data analysis, model selection, training & testing.

- Check notebook here [iris_ml](https://github.com/DonMarvex/iris_data/blob/main/iris_ml.ipynb)

Import the joblib library and save model

```Python
from joblib import dump, load
dump(trained_model, 'filename.joblib')
```

Load joblib anywhere using python
```Python
saved_model = load('filename.joblib')
```

The saved model can then be used to test new samples of data.