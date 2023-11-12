# Cloudcomputing_Team_4

# L&T Vehicle Loan Default Prediction

## Team
* Abhinav Botla
* Ajith Gannamaneni
* Hrushikesh Dandge
* Mitra Buggaveeti
* Prateek Chanddra

## Project artifact repository:
Git Link : https://github.com/mitrabuggaveeti/Cloudcomputing_Team_4

## Dataset Kaggle:
Vehicle Loan Default Prediction : https://www.kaggle.com/datasets/mamtadhaker/lt-vehicle-loan-default-prediction

## Project Scope:

The specific problem that the machine learning component aims to address is the prediction of the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Installments) on the due date. The financial institution is facing significant losses due to loan defaults, leading to tightened vehicle loan underwriting and increased rejection rates. In order to proactively address this issue and optimize the loan approval process, the organization aims to leverage machine learning to develop a sophisticated credit risk scoring model. This model's primary objective is to accurately predict the probability of a loanee or borrower defaulting on a vehicle loan, specifically within the initial EMI on the due date.

The machine learning model will utilize information from various datasets, including loanee information (demographic data), loan information (disbursed amount, asset cost, employment type), and bureau data & history (bureau score, number of active accounts, status of other loans, credit history, etc.). By analyzing these factors, the model will identify important determinants that contribute to the likelihood of loan default.

The project aligns with the educational program goals of AWS Academy Cloud Foundations and Data Engineering by incorporating key elements of data analysis, machine learning, and cloud computing. Specifically, it involves:

* Data Engineering: The project requires handling and processing large datasets containing diverse information about loan applicants. This involves data cleaning, transformation, and integration to create a cohesive dataset for model training.

* Machine Learning: The core of the project involves developing a predictive model using machine learning algorithms. This includes selecting appropriate algorithms, feature engineering, model training, and evaluation.

* Cloud Computing: The use of AWS services can enhance the scalability, flexibility, and efficiency of the project. Cloud services like Amazon S3 for storage, AWS Glue for ETL (Extract, Transform, Load), and SageMaker for machine learning model deployment can be incorporated.

* Analytics and Insights: The project aims to provide valuable insights into the determinants of vehicle loan default. This aligns with the goal of deriving actionable intelligence from data, a key aspect of data analytics.

* Risk Management: The project directly addresses the financial institution's need for better credit risk assessment. This aligns with the broader theme of risk management in data-driven decision-making, a crucial aspect covered in the educational program.

By successfully completing this project, the financial institution can optimize its loan approval process, reduce default rates, and make informed decisions based on predictive analytics. Notably, the anticipated outcome includes a substantial reduction in default rates, an important metric that directly impacts the institution's financial health. By accurately identifying the key determinants of default within the critical period of the first EMI on the due date, the model empowers the institution to proactively address risk factors and refine its underwriting criteria. This, in turn, contributes to a more robust lending portfolio, fostering sustainable growth and minimizing the financial challenges associated with loan defaults. Additionally, identifying key determinants of default can contribute to ongoing efforts to minimize risks associated with vehicle loans.


## Domain:

The domain that the project is focused on is the financial services industry, particularly in the area of credit risk assessment and prediction for vehicle loans. Here are the key characteristics, challenges, and opportunities within this domain:

Key Characteristics:

1. Credit Risk Assessment: Financial institutions, such as banks and credit unions, are involved in providing vehicle loans to individuals. These loans are a significant source of revenue for these institutions. However, they also come with the risk of borrowers defaulting on their loan payments, leading to financial losses.

2. Data-Driven Decision Making: The financial industry has increasingly turned to data-driven approaches to assess credit risk. Machine learning and predictive modeling have become essential tools to assess the likelihood of loan default accurately.

3. Regulatory Environment: The financial industry is highly regulated, and there are strict guidelines and regulations in place to ensure responsible lending practices. Accurate credit risk assessment is crucial to compliance with these regulations.

### Challenges:

1. Loan Default Risk: One of the primary challenges in the industry is the risk of borrowers defaulting on their vehicle loans. This can result in substantial financial losses for the lending institutions.

2. Data Quality and Quantity: Ensuring the availability of high-quality and sufficient data for training predictive models can be challenging. Inaccurate or incomplete data can impact the model's performance.

3. Model Interpretability: Building accurate predictive models is important, but it is equally important to make these models interpretable so that financial institutions can understand the factors influencing loan default.

### Opportunities:

1. Improved Risk Assessment: By developing an accurate credit risk scoring model, financial institutions can make more informed lending decisions, leading to a reduction in loan defaults and losses.

2. Efficient Loan Approval: Automation of the credit risk assessment process can lead to more efficient and quicker loan approval processes, improving customer satisfaction and operational efficiency.

3. Data-Driven Insights: Through data analysis, the project can provide insights into the key determinants of loan default, helping financial institutions design risk management strategies and refine underwriting standards.

### Stakeholders:

The stakeholders in this domain who will benefit from the project include:

1. Financial Institutions: Banks, credit unions, and other lending institutions are the primary stakeholders. They stand to benefit from the project by reducing losses due to loan defaults, streamlining the loan approval process, and making more informed lending decisions.

2. Borrowers: Accurate credit risk assessment can lead to fairer lending practices. Creditworthy borrowers are less likely to be rejected, improving their access to credit.

3. Regulatory Bodies: Regulatory authorities in the financial sector benefit from more accurate and responsible lending practices that align with regulatory guidelines.

In summary, the project aims to address the specific problem of vehicle loan default prediction by developing an accurate credit risk scoring model, ultimately benefiting financial institutions, borrowers, and regulatory authorities in the financial services industry.

## Literature Review:

Conducted a literature review of several research papers, articles, and books related to the domain of credit risk assessment and prediction for vehicle loans. The purpose was to stay informed about the latest advancements and best practices in this field. Here are the summaries and insights from the sources referenced.


* Credit Risk: Definition, Role of Ratings, and Examples (https://www.investopedia.com/terms/c/creditrisk.asp)

1. Credit Risk Definition: Credit risk is defined as the likelihood of a financial loss occurring due to a borrower's failure to repay a loan, impacting cash flows and collection costs.
2. Creditworthiness Factors: Lenders assess credit risk by analyzing factors such as credit history, capacity to repay, capital, loan conditions, and collateral, known as the "five Cs of credit."
3. Impact on Interest Rates: Borrowers with higher perceived credit risk are subject to higher interest rates, while those with strong credit profiles receive more favorable loan terms.
4. Role of Credit Rating Agencies: Bond credit-rating agencies, such as Moody's and Fitch, evaluate the credit risks of bond issuers and municipalities, influencing investors' decisions based on credit ratings.

* Credit Scoring with Machine Learning  (https://medium.com/henry-jia/how-to-score-your-credit-1c08dd73e2ed)
1. Project Motivation: Creditworthiness is crucial for service providers, and credit scoring simplifies this assessment by developing a scorecard.
2. Data Exploration and Feature Engineering: The article explains how to handle missing values, treat outliers, and group features through binning.
3. Weight of Evidence (WoE) and Information Value (IV): These concepts are introduced to assign unique values to categorical variables and measure predictive power for feature selection.
4. Model Fitting and Scorecard Calculation: Logistic regression is used, and data processing significantly improves accuracy.

* Machine Learning: Challenges, Lessons, and Opportunities in Credit Risk Modeling
(https://www.moodysanalytics.com/risk-perspectives-magazine/managing-disruption/spotlight/machine-learning-challenges-lessons-and-opportunities-in-credit-risk-modeling)
1. Machine learning has become essential in credit risk modeling thanks to increased data availability and computing power.
2. Machine learning models excel in predicting defaults, especially when incorporating behavioral data like credit line usage and loan payment behavior.
3. Challenges with machine learning models include overfitting, complex and less interpretable predictions, and sensitivity to outliers.

* Designing next-generation credit-decisioning models (https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/designing-next-generation-credit-decisioning-models)
1. The article discusses the importance of advanced credit-decisioning models in the banking sector, highlighting their ability to make precise lending decisions and enhance operational efficiency.
2. Challenges in transitioning to new credit models include data limitations, subjective assessments, and inflexible legacy models, but the benefits, such as increased revenue and reduced credit losses, are significant.
3. Banks that don't adopt next-generation credit models may face challenges due to outdated historical data and increasing competition from fintech companies and challenger banks.
4. The article outlines four best practices for designing credit models, including implementing a modular architecture, expanding data sources, mining data for credit signals, and leveraging business expertise to improve credit decisions and meet future challenges.

* RESPONSIBLE LENDING BY WORLD BANK (https://documents1.worldbank.org/curated/en/596151468336064796/pdf/832840WP0GFDR00Box0382083B00PUBLIC0.pdf)
1. The paper outlines government interventions for promoting responsible lending, encompassing information provision, consumer education, lender behavior requirements, and regulatory loan limits.
2. Regulators establishing responsible lending frameworks must comprehensively address various aspects, understand retail credit markets, and conduct impact assessments to avoid potential negative consequences like financial exclusion or increased credit costs.
3. The paper emphasizes the need for better data on lending markets and consumer behavior to inform regulatory rules that encourage responsible lending while maintaining financial inclusion and credit market growth.


## DataSources:

Potential Data Sources:

1. Credit Bureau Data: Credit bureaus are primary data sources for assessing an individual's creditworthiness. These bureaus collect and maintain credit-related information on individuals, such as credit scores, outstanding debts, and payment history. Access to such data can be crucial for building a credit risk scoring model. Many financial institutions subscribe to credit bureaus' services to obtain this data.

2. Loan Application Data: Financial institutions maintain records of loan applications, including applicant information, loan details, and application outcomes. This data source can be valuable in understanding loan approval and default patterns.

3. Public Datasets: As in the case of the Kaggle dataset you mentioned, there are often public datasets available that contain anonymized loan application and default data. These datasets can be useful for model development and research.

Challenges in Choosing the Domain and Dataset:

1. Data Quality: Ensuring the quality of the data is a significant challenge. Incomplete, inaccurate, or outdated data can hinder the model's accuracy and reliability. Data cleansing and preprocessing are critical steps to address this challenge.

2. Data Privacy and Compliance: Handling personal and financial data comes with strict privacy and compliance requirements. Ensuring data is handled in compliance with regulations such as GDPR, HIPAA, or industry-specific standards is essential.

3. Data Availability: Depending on the sources, data availability may be limited or costly. Some financial institutions may be reluctant to share their data due to privacy concerns or competitive reasons.

The data sources for this project can be obtained from the following link on Kaggle: https://www.kaggle.com/datasets/mamtadhaker/lt-vehicle-loan-default-prediction. 
The dataset contains information about loan applicants, loan details, and bureau data, which are essential for building a credit risk scoring model.


## Domain-specific Challenges:
## KPI’s: 


