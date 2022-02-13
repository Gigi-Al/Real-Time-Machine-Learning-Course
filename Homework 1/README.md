Homework 1

report (pdf file) that explains your answers for each problem. The report MUST contain the link to your Github repository to access the source code you have developed for this homework. Your report should contain your name, student ID, and homework number. (2) a second pdf file that contains both source codes, results, and plots you have developed and plotted for this homework. You can easily generate this pdf in Jupyter Lab or Jupyter Notebook (sample pdf provided on Canvas.). The pdf file name should contain your name, student ID, and homework number.
In your report, provide separate and clear responses for each problem. Make reasonable assumptions where necessary and clearly state them! Be sure to show all the work involved in deriving your answers! If you just give a final answer without explanation, you may not receive credit for that question. 
You may discuss concepts with your classmates. This fosters group learning and improves the class’ progress. However, make sure to submit your own independent and individual solutions. 
 

Problem 1 (20 pts):

1.a Take several pictures of red, blue, and green items with your phone or other digital cameras (or download some from the internet, if a camera isn’t available).

 

1.b Load each image, and convert it to a tensor.

 

1.c. For each image tensor, use the .mean() method to get a sense of how bright the image is.

 

1.d Take the mean of each channel of your images. Can you identify the red, green, and blue items from only the channel averages?

 

Problem 2 (40 pts):

In our temperature prediction example, let’s change our model to a non-linear system. Consider the following description for our model:

 

w2 * t_u ** 2 + w1 * t_u + b.

 

2.a Modify the training loop properly to accommodate this redefinition. 

 

2.b Use 5000 epochs for your training. Explore different learning rates from 0.1 to 0.0001 (you need four separate trainings). Report your loss for every 500 epochs per training.

 

2.c Pick the best non-linear model and compare your final best loss against the linear model that we did during the lecture. For this, visualize the non-linear model against the linear model over the input dataset, as we did during the lecture. Is the actual result better or worse than our baseline linear model?

 

 

Problem 3 (40 pts):

3.a. Develop preprocessing and a training loop to train a linear regression model that predicts housing price based on the following input variables:

 

area, bedrooms, bathrooms, stories, parking

 

For this, you need to use the housing dataset. See example on Canvas. Identify the best parameters for your linear regression model, based on the above input variables. In this case, you will have six parameters:

U=W5*X5 + W4*X4 + W3*X3 + W2*X2 + W1*X1 + B

 

3.b Use 5000 epochs for your training. Explore different learning rates from 0.1 to 0.0001 (you need four separate trainings). Report your loss for every 500 epochs per each training.

 

3.c Pick the best linear model (the one with the smaller final loss) and visualize it over the input dataset, as we did during the lecture.
