# Bank-Marketing-Analytics

**Project Overview**

Bank Marketing Analytics is a data science project focused on predicting the likelihood of a customer subscribing to a bank's term deposit product. Term deposits are a significant revenue stream for banks, and outreach campaigns—including telephonic marketing—are used to encourage customers to invest. However, telephonic campaigns are resource-intensive, necessitating the need for a predictive model to identify high-potential customers. The project aims to increase conversion rates, reduce campaign costs, and enhance marketing efficiency by targeting customers most likely to subscribe.

**Problem Statement**

The goal is to identify customers most likely to subscribe to a term deposit by analyzing various features in the dataset, which was sourced from a Portuguese banking institution's direct marketing campaigns. The data includes demographic and socio-economic attributes of clients contacted for term deposit subscriptions.

**Dataset**

The dataset includes the following columns:

Demographic features: age, job, marital status, education
Financial information: balance, housing loan status, personal loan status, default status
Campaign details: contact method, day, month, duration, number of contacts in the current and previous campaigns, and outcome of previous campaigns
Target Variable: y - whether the client subscribed to a term deposit (yes/no)

**Exploratory Data Analysis (EDA)**

EDA helped identify important patterns and relationships in the data:

**1. Age vs. Subscription**: Bar plot showing subscription rate by age groups.
**2. Job Type vs. Subscription**: Bar plot showing subscription counts by job type.
**3. Age vs. Balance**: Scatter plot highlighting the relationship between age and account balance.
**4. Marital Status vs. Subscription**: Heatmap showing subscription rates across different marital statuses.
**5.Campaign vs. Subscription**: Comparison of subscription rates across different campaign contacts.
**6.Previous Campaign Outcome vs. Subscription**: Bar plot showing current campaign success based on the outcome of previous campaigns.
**7.Default Status vs. Subscription**: Count plot of default status and its relation to subscription.

**Model Development**

Two classification models were trained and evaluated on the data:
Logistic Regression
Support Vector Machine (SVM)

**Model Evaluation Metrics**

Logistic Regression
Accuracy: 90%


Support Vector Machine (SVM)
Accuracy: 92%

**Conversion Rate Analysis**

Baseline Conversion Rate
The Baseline Conversion Rate (before using the predictive model) was 11.68%, indicating that only 11.68% of customers subscribed without targeted outreach.

Combined New Conversion Rate
**With model predictions guiding targeted outreach, the Combined New Conversion Rate increased to 78.80%. This indicates a significant improvement, demonstrating the model’s effectiveness in identifying potential subscribers, thus making telephonic campaigns more efficient and cost-effective.**

**Project Results and Conclusion**
The project demonstrates the power of predictive analytics in banking marketing campaigns. Using machine learning models to identify high-potential leads for term deposit products allowed for a substantial increase in conversion rates—from a baseline of 11.68% to 78.80%. This not only enhances marketing efficiency but also optimizes the resource allocation for customer outreach, potentially lowering costs and improving revenue from term deposits.**

**Technologies Used**

Programming Language: Python
Libraries: pandas, scikit-learn, matplotlib, seaborn
Modeling Techniques: Logistic Regression, Support Vector Machine (SVM)
