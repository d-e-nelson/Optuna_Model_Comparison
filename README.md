## Optuna: The Agnostic Tuner

This project seeks to give a brief explination on what Optuna is and how it compares to of of the more common hyperparameter tuning methods. The goal is to highlight the pros and cons of each method while putting a spotlight on the out of the box utility that Optuna offers. 

## Interperting Result Scores
The final reported scores for each model are in the formate of Exponential Root Mean Square Log Error.
The predictions will be off by a factor of the score. 

## Calculating the prediction range. 
For this example we will use a resulting Exp RMSLE of 1.171

### Calculate the upper bound:
1.171 - 1 = 17.1%

### Calculate the lower bound:
1/1.171 = 0.8539
1 - 0.8539 = 14.61%

### Results:
The results could fall within 17.1% above or 14.61% below the ideal prediction. 



## Resources
Optuna Documentation: [Link](https://optuna.readthedocs.io/en/stable/)<br>
Optuna Dashboard: [Link](https://github.com/optuna/optuna-dashboard)

## Slides

<p align="left">
  <img src="https://github.com/d-e-nelson/Optuna_Model_Comparison/blob/main/images/slide%201.png"
       alt="Slide 1"
       width="1000" />
</p>

<p align="left">
  <img src="https://github.com/d-e-nelson/Optuna_Model_Comparison/blob/main/images/Slide%202.png"
       alt="Slide 2"
       width="1000" />
</p>

<p align="left">
  <img src="https://github.com/d-e-nelson/Optuna_Model_Comparison/blob/main/images/Slide%203.png"
       alt="Slide 3"
       width="1000" />
</p>

<p align="left">
  <img src="https://github.com/d-e-nelson/Optuna_Model_Comparison/blob/main/images/slide%204.png"
       alt="Slide 4"
       width="1000" />
</p>

<p align="left">
  <img src="https://github.com/d-e-nelson/Optuna_Model_Comparison/blob/main/images/Slide%205.png"
       alt="Slide 5"
       width="1000" />
</p>

<p align="left">
  <img src="https://github.com/d-e-nelson/Optuna_Model_Comparison/blob/main/images/slide%206.png"
       alt="Slide 6"
       width="1000" />
</p>

<p align="left">
  <img src="https://github.com/d-e-nelson/Optuna_Model_Comparison/blob/main/images/slide%207.png"
       alt="Slide 7"
       width="1000" />
</p>
