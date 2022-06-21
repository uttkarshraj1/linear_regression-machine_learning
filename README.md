# Linear Regression

**Linear Regression with One Variable**

1) In this exercise, we have one variable, X, and we are building a model to predict one output, Y.

2) From the root directory of the assignment’s code, navigate to the folder “assgn_1_part_1/1_one_variable”.

3) The main program will be run from ml_assgn1_1.py. Your first task is to run the main file, by executing the command
“python ml_ assgn1_1.py” in a terminal.

4) You will see a graph open displaying the changing gradient of your hypothesis. When gradient descent has finished,
you will see the cost obtained with the theta values used at each iteration. 

5) Both the hypothesis and the cost graph will be flat because we need to calculate our hypothesis. 


**Linear Regression with Multiple Variables**

1) From the root directory of the assignment’s code, navigate to the folder “assgn_1_part_1/2_multiple_variables”. 

2) In this part, we will be using the script ml_assgn1_2.py.

3) In this exercise, we are looking at house price data. x0 corresponds to the bias, x1 is the area of the house in square feet and x2 is the number of bedrooms. 

4) If you open ex1data2.txt you will see there is a large difference between the values of x1 and x2. 

 **Regularized Linear Regression**
 
1) From the root directory of the assignment’s code, navigate to the folder “assgn_1_part_1/3_regularized_linear_regression”. 

2) In this part, we will be using the script ml_assgn1_3.py.

3) Note that the punishment for having more terms is not applied to the bias. 

4) This cost function has been implemented already in the function compute_cost_regularised. 

5) Modify gradient_descent to use the compute_cost_regularised method instead of compute_cost. 

6) Include the relevant lines of the code in your report and a brief explanation

7) After gradient_descent has been updated, run ml_assgn1_3.py. 

8) This will plot the hypothesis function found at the end of the optimization.

9) First of all, find the best value of alpha to use in order to optimize best. Report the value of alpha that you found in your
report.

10) Next, experiment with different values of and see how this affects the shape of the hypothesis.

11) Note that gradient_descent will have to be modified to take an extra parameter, l (which represents λ, used for regularization).

12) Include in your report the plots for a few different values of and comment.
