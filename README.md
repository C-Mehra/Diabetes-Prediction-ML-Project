# Project Title

Diabetes Prediction System



## Project Description

The Diabetes Prediction System revolves around my utilization of Google Colab to craft a machine learning algorithm using various Python libraries. I focused on the Logistic Regression model, evaluating its accuracy through an accuracy score to gauge the reliability of predictions.

Subsequently, I delved into PyCharm, incorporating Django to fashion an interactive and intuitive temporary web page. This page seamlessly interfaces with the previously crafted model, enabling users to input health data and receive instantaneous predictions about the likelihood of having diabetes.

This project is a personal endeavor aimed at contributing to proactive healthcare, offering a user-friendly tool for early diabetes risk assessment. The system provides valuable insights for both individuals and healthcare professionals, fostering a proactive approach to preventive care.


### Steps followed to transform and manipulate data

1. 1. *Research and Data Collection:*
   - Conducted research on diabetes prediction algorithms and relevant health parameters.
   - Gathered a dataset containing relevant features such as glucose levels, BMI, age, etc., necessary for diabetes prediction.

2. *Data Preprocessing:*
   - Imported the dataset into Google Colab.
   - Explored the dataset to understand its structure and characteristics.
   - Handled missing values, outliers, and performed feature scaling if necessary.
   
3. *Machine Learning Model Development:*
   - Implemented a machine learning algorithm using Python libraries (e.g., NumPy, Pandas, Scikit-learn) within Google Colab.
   - Chose Logistic Regression as the predictive model due to its simplicity and interpretability, which aligns well with healthcare applications.
   - Split the dataset into training and testing sets to evaluate the model's performance.
   - Trained the Logistic Regression model on the training data.
   - Tuned hyperparameters if needed to optimize model performance.
   - Evaluated the model's accuracy using appropriate metrics such as accuracy score, precision, recall, and F1-score.

4. *Web Interface Development:*
   - Installed Django framework within PyCharm for web development.
   - Created a Django project and an application within the project.
   - Designed an interactive web page using HTML, CSS, and possibly JavaScript for user input.
   - Integrated the trained Logistic Regression model into the Django application.
   - Established communication between the web interface and the machine learning model to facilitate predictions.
   - Implemented error handling and validation mechanisms to ensure data integrity and user experience.

5. *Testing and Deployment:*
   - Conducted thorough testing of the web application to ensure functionality and usability.
   - Debugged and refined the application based on testing feedback.
   - Deployed the web application on a local server or cloud platform for accessibility.

6. *Documentation and Presentation:*
   - Documented the entire project, including data preprocessing steps, model development, web interface creation, and deployment procedures.
   - Prepared a presentation summarizing the project objectives, methodology, results, and future enhancements.
   
7. *Future Enhancements:*
   - Considered potential future enhancements such as integrating additional machine learning models for comparison, incorporating more features for improved prediction accuracy, and enhancing the user interface for better user experience.

## Step by Step Understanding
a) Libraries

I downloaded various Python libraries which are required to create a prediction model for this project.

![Libraries](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/7d556fad-7f8a-4899-89bb-e36c1f44b352)


b) Heatmap

I created a heatmap to check if we have any missing values in the data set used for this project.

![Heatmap](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/d97cf0be-5b99-45c7-9d46-7fdb58b12156)

c) Correlation matrix

After making sure that we dont have any missing values, we create a correlation matrix to check how the data is correlated amongst different data points.

![Correlation Matrix](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/fc88d7bb-b5b7-4c1f-bc21-22262379b62d)

d) Visualizing the correlation

To get a better idea of the correlation, I created a heatmap of the correlation to visualize the coorelation.

![Visualizing the correlation](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/39e839c0-b5a3-4703-9547-7d5f83c0a188)

e) Training the model

After checking the correlation, I trained the data using Train Test Split wherein I divided the data into Test and Train. It is notable that 20% of the data was tested for this particular model. Then I trained the model using Logistics Regression.

![Training the Model](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/c9d81e8d-aa5e-4c09-bf53-841cfe209e6b)

f) Prediction and Accuracy score

After training the model on Logistic Regression, we predict the outcome. Finally I needed to check how accurate the outcomes were for which I calculated the accuracy score.

![Prediction and Accuracy score](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/f9f40ecb-3a37-4cff-9259-9968312717ba)

g) Landing Page

I used Django in Pycharm to design this landing page. One can see the heading that says "Diabetes Prediction System" and at the bottom there is a button labelled as "Go" clicking on which will take us to the next page.

![Landing page](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/4507074e-b4f1-4c2d-8633-e5c012537f48)

h) Input Form

Once we press "Go", we come to this page which contains a form. The fields in this form are the columns from the data set which we trained on Logistics Regression. Once we fill all the information we will get an output which will determine if the user has Diabetes or not.

![Input Form](https://github.com/C-Mehra/Diabetes-Prediction-ML-Project/assets/151509146/1931e3bc-85c5-4797-83f6-a432d8af4c5b)


# Insights

1. *Importance of Data Quality:* 

The accuracy of the prediction model heavily relies on the quality of the dataset. Ensuring that the data is clean, relevant, and representative of the target population is crucial for developing an effective predictive model.

2. *Model Selection and Evaluation:* 

Choosing the appropriate machine learning model is essential. In this project, Logistic Regression was selected for its simplicity and interpretability, making it suitable for healthcare applications. However, it's important to evaluate multiple models and select the one that provides the best performance based on relevant metrics.

3. *Integration of Machine Learning with Web Development:* 

Integrating a machine learning model into a web application requires seamless communication between different technologies. The project demonstrates the integration of Python-based machine learning algorithms with web development frameworks like Django, providing users with an interactive interface for making predictions.

4. *User-Centric Design:* 

The success of the web application hinges on its user interface and user experience. Designing an intuitive and user-friendly interface is essential for encouraging user engagement and adoption. Additionally, implementing error handling and validation mechanisms ensures data integrity and enhances the overall user experience.

5. *Proactive Healthcare:* 

The project contributes to proactive healthcare by providing individuals and healthcare professionals with a tool for early diabetes risk assessment. By leveraging machine learning techniques, the system empowers users to take proactive measures for preventive care, potentially reducing the incidence and impact of diabetes-related complications.

Overall, the Diabetes Prediction System project highlights the intersection of machine learning, web development, and healthcare, demonstrating the potential for technology to improve proactive health management and decision-making.

