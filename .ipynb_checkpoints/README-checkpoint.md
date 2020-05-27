 
#  Electric Motor Temperature Estimation

The aim of this project is to apply machine learning to estimate the temperature of the rotor of a electric motor (PMSM).

Most electric cars use permanent magnet synchronous motors (PMSM). The main motor components lack accurate temperature monitoring. High temperatures must be avoided at all times otherwise the consequences could be failing components like stator winding insulation which may melt and the permanent magnet could suffer from irreversible demagnetization. At the moment safe operation of the motor is ensured by oversized materials which increases production costs.

By using linear regression model we can achieve a simple model with time-invariant properties which can be directly implemented in the real time control system of the motor.


If you are interested in this project and would like to discuss its details, please contact me directly at: 

*  [Email](abisixto@gmail.com)
*  [Linkedin](https://www.linkedin.com/in/abigail-sixto-b4b7211b/)


### Executive Summary

This project was inspired by a kaggle competition about the estimation of motor temperatures using machine learning.
The [dataset](https://www.kaggle.com/wkirgsn/electric-motor-temperature) is obtained from a technical lab at Paedorn University (Germany). 

The content of the notebook :
- Data extraction and exploration

- Data understanding and visualitazion

- Modelling linear regression

- baseline modelling
- Feature Engineering 2nd linear model
- Random Forest Regressor 
 So far this model has the best metrics
 
- Models evaluation and best model selection

- Testing best model

- Aplication and deployability

- Future improvements









### More Information

The same dataset has inpired other publications:

[Deep Residual Convolutional and Recurrent Neural Networks for Temperature Estimation in Permanent Magnet Synchronous Motors](https://www.researchgate.net/publication/331982128_Deep_Residual_Convolutional_and_Recurrent_Neural_Networks_for_Temperature_Estimation_in_Permanent_Magnet_Synchronous_Motors)
[Empirical Evaluation of Exponentially Weighted Moving Averages for Simple Linear Thermal Modeling of Permanent Magnet Synchronous Machines](https://www.researchgate.net/publication/331976678_Empirical_Evaluation_of_Exponentially_Weighted_Moving_Averages_for_Simple_Linear_Thermal_Modeling_of_Permanent_Magnet_Synchronous_Machines)


