# Forecasting-pharmaceutical-demand

Undergraduate thesis done under the supervision of Dr. Sultana Parvin. The work is a comparative study of multiple deep learning-based architectures and ensemble machine learning models to perform time series analysis of pharmaceutical sales data across a range of drugs catgories for model reliability and decision relevance.

# Models Used

1. LSTM
2. XGBoost
3. Random Forest
4. NEAT

# Instructions 

- Run `pip install -r requirements.txt` to install the required dependencies. 
- Each of the models has a separate notebook file for it in the directory. Run each notebook to reproduce the results of the particular model.
- The notebooks are designed to predict sales values of **one** drug at a time. To test other sales numbers, simply change the name of the drug, available in the notebooks as *column_name* or *TARGET_COL*.
