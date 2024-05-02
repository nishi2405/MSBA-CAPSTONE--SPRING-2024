# MSBA – CAPSTONE – Home Credit Default Risk 

## Introduction 
Home Credit is an international financial provider operating across nine countries, offering various loan types like point-of-sale, cash, and revolving loans to underserved borrowers. These individuals, classified as having limited or no credit history despite stable incomes, often face hurdles in accessing credit from traditional lenders. Home Credit's core belief is that everyone should have the opportunity to fulfill their aspirations without credit history acting as a barrier. The project's objective is to utilize borrower behavioral data to develop predictive models. These models will aid Home Credit in accurately assessing client risk and determining safe lending amounts, particularly for underserved borrowers with minimal credit history. The ultimate goal is to provide financial support to customers, fulfilling their dreams while maintaining responsible lending standards.

## Business Problem 

Home Credit is dedicated to overcoming the challenges faced by individuals with insufficient credit histories, who often struggle to secure loans and are susceptible to exploitation by untrustworthy lenders. By leveraging alternative data sources like telco and transactional records, Home Credit aims to assess its clients' repayment capacities accurately. This approach not only broadens financial inclusion for the unbanked population but also creates a secure and positive borrowing experience. Home Credit's mission is to empower this marginalized segment by providing access to loans while minimizing the risks associated with lending, ultimately fostering a more inclusive and supportive financial environment.

## Project Objective

The primary goal of this project is to develop a predictive analytics solution using supervised learning methods to assess the creditworthiness of loan applicants. The objective is to utilize a classification algorithm to forecast whether an applicant will fulfill their loan commitments or default. The target variable for this supervised classification model will be binary, indicating whether the applicant is considered capable of repayment or not. This initiative aims to provide a reliable tool for financial institutions to make informed lending decisions, ultimately reducing default risks and optimizing their loan portfolios.

## Solution 

This study explored the development of a robust framework for assessing loan default risk within Home Credit. Leveraging a combination of application and Bureau datasets, a multi-pronged approach was employed, encompassing data cleaning, exploratory data analysis (EDA), hypothesis testing, and machine learning modeling.

The EDA phase involved a thorough examination of borrower characteristics within the application dataset, alongside a deep dive into the transactional details captured in the Bureau data. This enabled the formulation and testing of relevant hypotheses, such as the potential influence of factors like gender, age, and occupation on default likelihood.

Following the EDA, the construction of predictive models was undertaken. Logistic regression, a well-established technique in credit risk assessment, was initially evaluated. Subsequently, the performance of more advanced models such as Random Forest, XGBoost, and LightGBM were assessed.  The core objective was to identify the model that demonstrated superior predictive power based on the established evaluation metrics employed by Kaggle.

Through this comprehensive analysis, valuable insights were extracted from Home Credit's loan data. This exploration culminated in the development of a framework for predicting loan default risk, with the most effective model identified based on Kaggle's scoring system.

## Contribution

During the project, I led the exploratory data analysis (EDA) phase, starting with data cleaning to effectively handle and impute missing values. I then proceeded to perform feature engineering on the two datasets, bureau and bureau balance. Through thorough exploration of the dataset, I utilized hypothesis testing techniques and visualizations to gain deep insights into the data.

Understanding the business requirements was crucial, and I provided solutions by interpreting model confusion matrices to evaluate performance and suggest improvements. One significant step was implementing the Logistic Regression model, which I documented meticulously in a comprehensive notebook write-up detailing methodologies and key insights derived from the analysis.

Conducting rigorous model evaluations, I identified the most effective model for predicting credit default risk based on established metrics and criteria. This process played a vital role in ensuring the project's success and aligning with our goals.

## Business Value

The predictive capabilities of the model empower Home Credit to proactively identify customers who may be at risk of defaulting on their loans. By leveraging Explainable AI (XAI), the model clarifies which predictors have the greatest impact on default likelihood, offering valuable insights for refining risk management strategies.

Modeling plays a crucial role in mitigating the risk associated with non-performing assets, thereby strengthening the company's financial performance by reducing losses attributed to defaults. Additionally, extending loans to underserved customers without credit history expands Home Credit's customer base and revenue streams, promoting inclusive growth and financial empowerment.

Adopting technology and machine learning in the financial sector not only drives business expansion but also streamlines operations, leading to improved efficiency and customer service. Through an optimized loan portfolio driven by this solution, Home Credit strategically allocates resources to applications with the highest anticipated returns relative to their associated risks, maximizing profitability while maintaining a prudent risk profile.

Moreover, enhanced profitability stems from refined risk assessment and portfolio optimization, allowing Home Credit to approve loans with favorable Risk-Adjusted Return on Capital (RAROC) values. This results in increased revenue generation while mitigating the negative impacts of defaults.

## Team Challenges

1.	Dealing with Missing Values: Managing missing values presents a hurdle, requiring careful consideration on whether to fill them using measures like mean, median, or mode, or treat them distinctly as a separate category like 'None', for each column with missing data.

2.	Selecting Models: The challenge in model selection arises from high correlations between predictors and the risk of multicollinearity. It's crucial to choose models that can effectively handle these challenges.

3.	Feature Prioritization: A primary challenge our team encountered was handling the extensive volume of data from numerous files, particularly during feature engineering. This complexity made it challenging to determine which features should be included in our predictive model.

4.	Resource Limitations: Resource constraints, such as limited computational power, posed challenges in scaling our analysis and implementing modeling techniques. Optimizing model training times and utilizing available resources efficiently required significant effort.

5.	Hyperparameter Tuning: Fine-tuning hyperparameters for the models is crucial for achieving a good fit with the dataset and optimal results. The challenge lies in identifying the most appropriate combination for each model to achieve the highest predictive accuracy.

## Key Takeways

1.	Gaining Insight from Visualized Hypotheses: Utilizing visualizations to unravel hypotheses played a pivotal role in our analysis, facilitating the interpretation of data patterns and relationships. The amalgamation of diverse datasets enabled a comprehensive examination of the problem, allowing for thorough analysis and exploration of potential solutions.

2.	Feature Engineering: Navigating extensive datasets underscored the importance of feature engineering in extracting meaningful insights and improving model performance, prompting exploration of various feature selection and extraction techniques.

3.	Model Optimization: Addressing class imbalance challenges, particularly the majority class problem, required the adoption of under-sampling methods to balance class distributions. Furthermore, optimizing model performance through model selection and hyperparameter tuning was crucial in achieving optimal results.

4.	Model Development and Performance Evaluation: From implementing machine learning algorithms like LG Boost to fine-tuning parameters and evaluating performance metrics, I enhanced my skills in model development and assessment, leading to informed decision-making based on results interpretation.

5.	Delivering Results Aligned with Business Needs: The results obtained were aligned with Home Credit's business requirements, ensuring that the analysis provided actionable insights to support decision-making processes.

