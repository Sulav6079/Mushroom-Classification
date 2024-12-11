# Mushroom Classification Project  

This project involves building a machine learning pipeline to classify mushrooms as **edible** or **poisonous** based on their characteristics. Using a dataset of 8,124 mushroom samples with 23 categorical features, we applied advanced machine learning models to achieve high classification accuracy.  

## Dataset  
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/uciml/mushroom-classification/data). Each sample includes features such as cap shape, color, odor, habitat, and others, along with the target label:  
- **'e'**: Edible  
- **'p'**: Poisonous  

## Preprocessing  
1. **Data Cleaning**:  
   - Imputed missing values in the `stalk-root` column using KNN Imputer.  
2. **Encoding**:  
   - Applied one-hot encoding for categorical variables, ensuring the dataset was fully numeric for machine learning models.  

## Models and Evaluation  
We implemented two machine learning models to classify mushrooms:  
- **Random Forest Classifier**: Achieved an accuracy of **100%**.  
- **XGBoost Classifier**: Achieved an accuracy of **100%**.  

Feature importance analysis was performed to identify the most critical factors influencing the classification.  

## Results  
- Both the models had the same accuracy score.

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/mushroom-classification.git
2. Install Dependencies:
   ```bash
   pip install -r requirements.txt  
3. Run the Jupyter notebook or Python script
   ```bash
   python mushroom_classification.py

**Future Improvements**
- Implement additional models like Neural Networks for potential performance gains.
- Perform hyperparameter optimization to fine-tune model accuracy further.



