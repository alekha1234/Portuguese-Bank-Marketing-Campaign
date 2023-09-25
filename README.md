# Portuguese Bank Marketing
![image](https://github.com/alekha1234/Portuguese_Bank/assets/131946539/c0a0eb4a-aeee-46aa-be54-43749db06256)

          ____DataSet Details___
- **Age** :- Age of Bank Customers.
- **Job** - What Type of job do Bank Customer.
- **Marital** - Maritial Status.
- **Education** - Education / Highest Qualification.
- **Default** - Customer has defaulted or not(make mistakes or not able to return loan).
- **housing** - Customer has House loan or Not.
- **loan** - customer has Personal Loan or Not.
- **Contact** - Communication Type.
- **Month** - Last Contact Month of the year.
- **day_of_week** - last contact day of week.
- **Duration** - last contact duration in seconds .
- **campaign** - number of contacts performed during this campaign and for this client.
- **pdays** - number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted).
- **previous** - number of contacts performed before this campaign and for this client.
- **poutcome** - outcome of the previous marketing Campaign.
- **emp.var.rate**- employment variation rate - quarterly indicator. 
- **cons.price.idx** - consumer price index - monthly indicator.
- **cons.conf.idx** - consumer confidence index - monthly indicator.
- **euribor3m** - euribor 3 month rate - daily indicator .
- **nr.employed** - number of employees - quarterly indicator.
- **y** - the client has subscribed a term deposit or not.


**Description:**
As a passionate data scientist, I had the opportunity to work on an exciting real-world project with a leading Portuguese bank. The project aimed to optimize the bank's marketing efforts by leveraging machine learning techniques. Here's an overview of my contributions and the project's key highlights:

**Objective:**
The primary goal of this project was to increase the effectiveness of the bank's marketing campaigns by identifying potential clients who were more likely to subscribe to term deposits. This involved analyzing a large dataset of client interactions and demographics.

**Key Achievements:**
1. **Data Exploration:** I conducted comprehensive exploratory data analysis (EDA) to gain insights into the dataset's characteristics. This step was crucial in understanding the features that could impact the marketing outcome.

2. **Data Preprocessing:** Data preprocessing played a vital role in preparing the dataset for machine learning. I handled missing values, encoded categorical variables, and performed feature scaling to ensure the data was ready for modeling.

3. **Feature Selection:** To improve model efficiency and interpretability, I employed feature selection techniques. This step helped identify the most relevant client attributes that influenced subscription decisions.

4. **Machine Learning Models:** I experimented with various machine learning algorithms, including logistic regression, random forests, and gradient boosting. The models were trained and fine-tuned to predict whether a client would subscribe to a term deposit.

5. **Model Evaluation:** Rigorous model evaluation using metrics such as accuracy, precision, recall, and F1-score ensured the model's reliability. I used techniques like cross-validation to assess generalization performance.

6. **Results Interpretation:** One of the project's highlights was the ability to interpret model results. I provided actionable insights to the bank's marketing team, highlighting the most influential factors affecting subscription decisions.

**Impact:**
By leveraging machine learning, my project delivered remarkable results for the Portuguese bank:
- Increased marketing campaign efficiency, resulting in higher subscription rates.
- Reduced marketing costs by targeting clients more likely to subscribe.
- Enhanced client engagement and satisfaction by tailoring marketing messages.


**Technologies Used:** Python, Pandas, Scikit-Learn, Data Visualization, Machine Learning, Data Analysis

# ----- CONCLUSION -----

The Random Forest model achieved the highest test accuracy (94.84 %) among all models, followed closely by XGBoost & Decision Tree with a test accuracy of 94 % & 92 % respectively. The Random Forest model also had the highest F1 score (94.90 %), indicating its overall good performance in terms of precision and recall. K_Nearest Neighbour, Decision Tree, and Gradient Boosting & XG - Boost also performed reasonably well with F1 scores above 90 % .

So that why i am prefering Random forest .
