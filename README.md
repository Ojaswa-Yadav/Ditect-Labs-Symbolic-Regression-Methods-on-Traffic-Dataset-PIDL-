# Ditect-Labs-Symbolic Regression on Traffic dataset

Summary 

In this research we implemented different forms of Symbolic Regression on the NGSIM dataset and compared the results of all the models. We implemented three different models for this research. 
1) Vanila Symbolic Regression with fine tuned parameters to include more operators in the function set. This produced elementary equations which weren't really helpful for thr research.
2) We implemented (DSO) Deep Symbolic Regression on our dataset. First we tried to implement it using TensorFlow but due to hardware issues and bottleneck of the code using Tensorflow v1.16 it colud not be implemented so we switched to DSo using PyTorch which produced good results although the MSE was a bit high.
3) Lastly we implemented machine Learning based PySr model which performed the best out of the three producing an RMSE of 0.5.



Week 1- Studying the concepts of Physics Informed Deep Learning and Symbolic Regression.

Week 2- Arranging the NGSIM dataset which was used for the research and pre-processing the dataset.

Week 3- Implementing the vanila Symbolic Regression model on our dataset at dt=1 and fine tuning it to get performance metrics (MSE). 

Week 4- Studying the concept of Deep Symbolic Optimization and how to implement it on TensorFlow.

Week 5,6- Starting the implementation of DSO using Tensorflow. Since DSO on Tensorflow is writen for Tensorflow version 1, it could not be implemented due to hardware issues.

Week 7,8- Understanding the alternative approach for this  and Implmenting DSO using Pytorch

Week 9,10- Fine tune the DSO using Pytorch method for our dataset to get better performance metric (MSE) and equations that can best define the relationship between our parameters.

Week 11,12- Implemeting ML based SyPy method on our dataset to get even better results and equations when compared with our previous two models with an Impressive RMSE.

Week 13- Fine tuning the PySr model by changing the operators in our function set to make it work on a wider range of equations . In the end PySr performed the best with a validation RMSE of 0.5
