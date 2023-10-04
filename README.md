# Learning machine learning

Video link - https://youtube.com/playlist?list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw&si=eXIjiSLJFEImUPjL

---

## Theory
<details> <summary>
Tutorial1 - What is machine learning
   
</summary>

   1. Humans have neurons in there brains
   2. when you tell baby that this is cow then specific neurons light up and their edges become strong as shown in the image, for car different set of neuron lights up.
    ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/321fd67b-1ae2-42a5-8524-9f049ad31661)

    ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/f8c73c6b-4fca-4951-b37e-b535835df001)

    3. Deep learning uses neural network similar to this
    4. Machine learning examples- scam email detection, alexa google assitant, google recomendations, driverless cars etc.

</details>

<details> <summary>
Tutorial2 - linear regression single variable
   
</summary>

   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/b56f1227-43a2-425f-b82e-93ad52390147)

</details>

<details> <summary>
Tutorial3 - linear regression multiple variable
   
</summary>

</details>

<details> <summary>
Tutorial4 - Gradient Descent and Cost function
   
</summary>

1. In linear regresssion we minimize the mean squared error as shown in the following figure
   
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/c29f0cb3-6308-40ba-86e7-85bed57c240c)

2. Mean squared error - actual data point - the predicted data point then square then sum then divde by n
3. The mean square error is one of the cost functions, y pred  mx +b, the equation looks as follows

   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/43448e39-268b-4721-b95a-2e9956a24c9a)

4. Gradient descent algorithm finds the best fit line for given training data set in minimum steps.
5. We start with certain values of m and b and find their cost which here is 1000. Now keep changing m and b till we reach the lower most point.
6. We are starting from the star and heading towards red dot
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/ea2f8b35-c21d-4402-a751-a65e6650d77d)
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/2e1caa40-42e5-4ab0-b9db-a9319afa069d)
7. We take partial derivative of the mean square error wrt m and b  
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/02881d50-ae0f-48e8-b9da-4ab58dd6b940)
8. Now we know the slope of the cost function, we can try to minimize the cost
9. The next value of b and m can be calculted using following equations, point to remember is the step size keeps on decreasing with the slope as evident from the eqn. and the graph
    ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/7f33c594-29dd-4250-bd54-92e43f1e9df6)
    ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/1a7db5e8-7e27-4700-807b-03ccee77bb44)
10. Follow the code for implementation
    

</details>

<details> <summary>
Tutorial5 - save model using joblib and pickle

</summary>



</details>

<details> <summary>
Tutorial6 - Dummy variables & One Hot encoding
   
</summary>

1. Suppose you have town names as your input and the prices vary with them
2. We need to encode them as numbers,but if we encde them as integers machine can make assumptions such as town a < town b or town a + town b = town c during training. 
3. Nominal varibales are subcategory of categorical variables and nominal variables dont have any numeric order or mathematical relationship between them.
4. The second type is called ordinal varibales which has some sort of numeric order.
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/fed4244e-0121-44a0-8c3f-cae794a02b33)
5. Simple integer encoding wont work on the nominal variables so we use one hot encoding
6. We create three categories and assign them either one or zeros
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/0b84aa2a-ee6c-4fc4-a935-4379b48a2d6e)
</details>

<details> <summary>
Tutorial7 - Training and testing data
   
</summary>
1. We need to split training and testing data so that we can verify our model on the data that our model havent seen before 
2. 

</details>

<details> <summary>
Tutorial8 - Logistic Regression
   
</summary>
1. The prediciton values are not continous like linear regression bit are categorical
2. continous regression exaple - house prices, categorical eg- which party will a person vote for, or is the email spam or not
3.  Simple yes or no - binary classification, multiple categories - multiclass classification
4.  In an age vs boought insurace  or not problem we cant use linear regression as shown in figure

   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/5152bbbb-f7c9-4946-bfa3-eeec58912bce)
5.  For above linear regression method we can simply say that above 0.5 is 1 and below 0.5 is 0 so it will work, but if their is even one exceptional case the above mehod fails.
6.  Sigmoid or logit funtion, can fit better
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/cb902c31-e407-4608-a0c7-ee1947b72de1)
   ![image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/f871fde8-15ef-4162-9cb7-9169fed05ed2)
7. The sigmoid funtion is in range 0 to 1
8. We replace the z by mx+b
   [image](https://github.com/takalkartejas/learning_machine_learning/assets/67382565/48b55b54-f19d-4691-9ee5-4eff38231ad4)
9. Refer code 

</details>

<details> <summary>
Tutorial8.2 - Logistic Regression(multiclass classification)
   
</summary>
1. Lets take 8x8 images of numbers and classify them as numbers
2. Refer code 

</details>
---
---

## Learning steps:
<details> <summary>
Tutorial2 - linear regression single variable
   
</summary>
1. create linear_regression.ipynb
2. download the csv file

</details>

<details> <summary>
Tutorial3 - linear regression multiple variable
   
</summary>
1. The linear equation for price will be 
   price = m1*area + m2*bedrooms + m3*age + b 

</details>

<details> <summary>
Tutorial4 - gradient decent
   
</summary>
1. Follow the folder

</details>
---

## Usefull commands:

  



