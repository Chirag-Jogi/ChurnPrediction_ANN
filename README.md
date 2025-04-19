# ChurnPrediction_ANN

Primary Goal:
The goal of this project is to predict customer churn in the banking sector using an Artificial Neural Network (ANN). By identifying customers who are likely to churn, businesses can implement proactive strategies to retain them, improving customer loyalty and reducing loss.

Solutions:

Data Preprocessing:

Worked with a real-world dataset (Churn_Modelling.csv) containing 10,000+ customer records with 14 features, such as credit score, geography, age, account balance, and product usage.

Preprocessed the data by handling missing values, encoding categorical features using Label Encoding (for gender) and One-Hot Encoding (for geography), and scaling numerical features using StandardScaler for better model performance.

Model Development:

Built a deep learning model using Keras with an Artificial Neural Network (ANN) architecture, including dropout layers to reduce overfitting.

Tuned the model’s hyperparameters and evaluated its performance using key metrics like accuracy, precision, recall, and F1-score to ensure it provides reliable predictions.

Model Serialization:

Saved the trained model and all preprocessing components (encoders, scalers) using Pickle and H5 formats, ensuring modularity and ease of deployment.

Deployment:

Developed an interactive Streamlit web app that allows users to input customer data and get real-time churn predictions.

Result:

Achieved a high-accuracy churn prediction model capable of classifying customers as likely to churn or stay.

Delivered a fully functional, user-friendly, and interactive prediction tool deployed via Streamlit, enabling businesses to make data-driven decisions to retain at-risk customers.
