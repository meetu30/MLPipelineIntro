# MLPipelineIntro
Machine Learning Pipeline in Python
The Python Notebook is about basic implementation of ML Pipeline, covering a scenerio showcasing the importance of ML Pipeline.

Steps involved in the notebook-
1. Load boston housing dataset

2. Running Ridge algorithm on scaled data (which obviously gives wrong results) versus train dataset 
(** while scaling data, ALWAYS do fit_transform or fit transform on train data, and predict on transformed test data. Now, this is where people MIGHT make mistake, and ML pipeline internally takes care of this scenerio)

3. Building basic pipeline

4. Building ML pipleine with Hyperparameter tuning using grid search on SINGLE model 

5. Building ML pipleine with Hyperparameter tuning using grid search on MULTIPLE models 
