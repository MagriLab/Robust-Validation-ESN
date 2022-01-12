# How the code works

In the file Validation_Short_Lorenz.ipynb validation is carried out. By changing the variable 'val' different validation strategies are called. Model-free and model-informed can be chosen by selecting the variable model_informed=True/False.

The validaiton strategies are implemented in Val_Functions.ipynb, while the model-free and model-informed Echo State Networks are implemented in Functions.ipynb and Functions_MI.ipynb respectively. 

Once all the run for the different validation strategies are carried out and the hyperparameters have been selected, the file Test_Short_Lorenz.ipynb evaluates the performance of the selected hyperparameters in the test stet.

Post processing is finally performed in PostProc_Short_Lorenz.ipynb.

More explanations regarding the code can be found throughout the scripts as comments.

## Other datasets

The dataset analysed here is the 'Short' 12 Lyapunov Times dataset of the Lorenz system. 

The other datasets: Lorenz-96, chaotic Kuznetsov and quasiperiodic Kuznetsov can be found inside the /source/data/ folder. Each dataset cointans the data 'U' and the time 't'.
For the other datasets the validation strategies parameters, the Lyapunov exponent of the system, and other relevant parameters have to be changed in the relative functions.

Apart from this, the structure of the validation for any dataset is the same of the Lorenz system.


