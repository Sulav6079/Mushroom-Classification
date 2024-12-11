![467460726_435528936292952_6332135180497093630_n](https://github.com/user-attachments/assets/21e7ddbe-a606-4870-8766-cc72a4ecaef9)


# Mushroom Classification Project  

This project involves building a machine learning model to classify mushrooms as **edible** or **poisonous** based on their characteristics. Using a dataset of 8,124 mushroom samples with 23 categorical features, we applied advanced machine learning models to achieve high classification accuracy.  

## Dataset  
The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/uciml/mushroom-classification/data). Each sample includes features such as cap shape, color, odor, habitat, and others, along with the target label:  

| **Feature**                     | **Description**                                                                 |
|----------------------------------|---------------------------------------------------------------------------------|
| **class**                       | Edible (e) or Poisonous (p)                                                     |
| **cap-shape**                   | Bell (b), Conical (c), Convex (x), Flat (f), Knobbed (k), Sunken (s)            |
| **cap-surface**                 | Fibrous (f), Grooves (g), Scaly (y), Smooth (s)                                 |
| **cap-color**                   | Brown (n), Buff (b), Cinnamon (c), Gray (g), Green (r), Pink (p), Purple (u), Red (e), White (w), Yellow (y) |
| **bruises**                     | Bruises (t) or No Bruises (f)                                                  |
| **odor**                        | Almond (a), Anise (l), Creosote (c), Fishy (y), Foul (f), Musty (m), None (n), Pungent (p), Spicy (s) |
| **gill-attachment**             | Attached (a) or Free (f)                                                       |
| **gill-spacing**                | Close (c) or Widespread (w)                                                    |
| **gill-size**                   | Broad (b) or Narrow (n)                                                        |
| **gill-color**                  | Black (k), Brown (n), Buff (b), Chocolate (h), Gray (g), Green (r), Orange (o), Pink (p), Purple (u), Red (e), White (w), Yellow (y) |
| **stalk-shape**                 | Enlarged (e) or Tapered (t)                                                    |
| **stalk-root**                  | Bulbous (b), Clubbed (c), Cup (u), Equal (e), Rhizomorphs (r), Missing (?)      |
| **stalk-surface-above-ring**    | Fibrous (f), Scaly (y), Silky (k), Smooth (s)                                   |
| **stalk-surface-below-ring**    | Fibrous (f), Scaly (y), Silky (k), Smooth (s)                                   |
| **stalk-color-above-ring**      | Brown (n), Buff (b), Cinnamon (c), Gray (g), Orange (o), Pink (p), Red (e), White (w), Yellow (y) |
| **stalk-color-below-ring**      | Brown (n), Buff (b), Cinnamon (c), Gray (g), Orange (o), Pink (p), Red (e), White (w), Yellow (y) |
| **veil-type**                   | Partial (p)                                                                    |
| **veil-color**                  | Brown (n), Orange (o), White (w), Yellow (y)                                   |
| **ring-number**                 | None (n), One (o), Two (t)                                                     |
| **ring-type**                   | Cobwebby (c), Ectomycorrhizal (e), Flaring (f), Large (l), Sheathing (s), Zonate (z) |
| **spore-print-color**           | Black (k), Brown (n), Buff (b), Chocolate (h), Green (g), Orange (o), Purple (p), White (w), Yellow (y) |
| **population**                  | Abundant (a), Clustered (c), Numerous (n), Scattered (s), Solitary (y), Varying (v) |
| **habitat**                     | Grasses (g), Leaves (l), Meadows (m), Paths (p), Urban (u), Waste (w), Woods (d) |


## Preprocessing  
1. **Data Cleaning**:  
   - Imputed missing values in the `stalk-root` column using KNN Imputer.  
2. **Encoding**:  
   - Applied one-hot encoding for categorical variables, ensuring the dataset was fully numeric for machine learning models.  

## Models and Evaluation  
We implemented two machine learning models to classify mushrooms:  
- **Random Forest Classifier**: Achieved an accuracy of **100%**.  
- **XGBoost Classifier**: Achieved an accuracy of **100%**.  

## Results  
- Both the models had the same accuracy score.

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/mushroom-classification.git
   
2. Run the Jupyter notebook or Python script
   ```bash
   Python-2 Project.ipynb
