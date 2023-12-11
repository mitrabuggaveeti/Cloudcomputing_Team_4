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

*  **Data Engineering:** The project requires handling and processing large datasets containing diverse information about loan applicants. This involves data cleaning, transformation, and integration to create a cohesive dataset for model training.

* **Machine Learning:** The core of the project involves developing a predictive model using machine learning algorithms. This includes selecting appropriate algorithms, feature engineering, model training, and evaluation.

* **Cloud Computing:** The use of AWS services can enhance the scalability, flexibility, and efficiency of the project. Cloud services like Amazon S3 for storage, AWS Glue for ETL (Extract, Transform, Load), and SageMaker for machine learning model deployment can be incorporated.

* **Analytics and Insights:** The project aims to provide valuable insights into the determinants of vehicle loan default. This aligns with the goal of deriving actionable intelligence from data, a key aspect of data analytics.

* **Risk Management:** The project directly addresses the financial institution's need for better credit risk assessment. This aligns with the broader theme of risk management in data-driven decision-making, a crucial aspect covered in the educational program.

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

## Literature Review


Conducted a literature review of several research papers, articles, and books related to the domain of credit risk assessment and prediction for vehicle loans. The purpose was to stay informed about the latest advancements and best practices in this field. Here are the summaries and insights from the sources referenced.

### 1. [Credit Risk: Definition, Role of Ratings, and Examples](https://www.investopedia.com/terms/c/creditrisk.asp)

- **Credit Risk Definition:** The likelihood of a financial loss due to a borrower's failure to repay a loan, impacting cash flows and collection costs.
- **Creditworthiness Factors:** Lenders assess credit risk based on credit history, capacity to repay, capital, loan conditions, and collateral (the "five Cs of credit").
- **Role of Credit Rating Agencies:** Bond credit-rating agencies evaluate credit risks, influencing investor decisions based on credit ratings.

### 2. [Credit Scoring with Machine Learning](https://medium.com/henry-jia/how-to-score-your-credit-1c08dd73e2ed)

- **Project Motivation:** Creditworthiness is crucial, and credit scoring simplifies assessment through a scorecard.
- **Data Exploration and Feature Engineering:** Discusses handling missing values, treating outliers, and grouping features through binning.
- **Weight of Evidence (WoE) and Information Value (IV):** Introduces concepts for assigning unique values to categorical variables and measuring predictive power.
- **Model Fitting and Scorecard Calculation:** Utilizes logistic regression, highlighting the significance of data processing for accuracy.

### 3. [Machine Learning: Challenges, Lessons, and Opportunities in Credit Risk Modeling](https://www.moodysanalytics.com/risk-perspectives-magazine/managing-disruption/spotlight/machine-learning-challenges-lessons-and-opportunities-in-credit-risk-modeling)

- Machine learning is crucial in credit risk modeling, excelling in predicting defaults, especially with behavioral data.
- Challenges include overfitting, complex and less interpretable predictions, and sensitivity to outliers.

### 4. [Designing next-generation credit-decisioning models](https://www.mckinsey.com/capabilities/risk-and-resilience/our-insights/designing-next-generation-credit-decisioning-models)

- Discusses the importance of advanced credit-decisioning models, challenges in transitioning, and benefits such as increased revenue and reduced credit losses.
- Outlines four best practices for designing credit models.

### 5. [RESPONSIBLE LENDING BY WORLD BANK](https://documents1.worldbank.org/curated/en/596151468336064796/pdf/832840WP0GFDR00Box0382083B00PUBLIC0.pdf)

- Outlines government interventions for promoting responsible lending, emphasizing the need for better data on lending markets and consumer behavior.
- Regulators establishing responsible lending frameworks must comprehensively address various aspects.

## DataSources:

### Potential Data Sources:

1. Credit Bureau Data: Credit bureaus are primary data sources for assessing an individual's creditworthiness. These bureaus collect and maintain credit-related information on individuals, such as credit scores, outstanding debts, and payment history. Access to such data can be crucial for building a credit risk scoring model. Many financial institutions subscribe to credit bureaus' services to obtain this data.

2. Loan Application Data: Financial institutions maintain records of loan applications, including applicant information, loan details, and application outcomes. This data source can be valuable in understanding loan approval and default patterns.

3. Public Datasets: As in the case of the Kaggle dataset you mentioned, there are often public datasets available that contain anonymized loan application and default data. These datasets can be useful for model development and research.

### Challenges in Choosing the Domain and Dataset:

1. Data Quality: Ensuring the quality of the data is a significant challenge. Incomplete, inaccurate, or outdated data can hinder the model's accuracy and reliability. Data cleansing and preprocessing are critical steps to address this challenge.

2. Data Privacy and Compliance: Handling personal and financial data comes with strict privacy and compliance requirements. Ensuring data is handled in compliance with regulations such as GDPR, HIPAA, or industry-specific standards is essential.

3. Data Availability: Depending on the sources, data availability may be limited or costly. Some financial institutions may be reluctant to share their data due to privacy concerns or competitive reasons.

The data sources for this project can be obtained from the following link on Kaggle: https://www.kaggle.com/datasets/mamtadhaker/lt-vehicle-loan-default-prediction. 
The dataset contains information about loan applicants, loan details, and bureau data, which are essential for building a credit risk scoring model.


## Domain-specific Challenges:

There are several domain-specific challenges that are need to be considered those are :
### 1. Data Security

- The dataset contains highly sensitive financial information, including account details and government IDs.
- Ensure robust data security measures, including encryption and access controls, to prevent unauthorized access.

### 2. Ethical Considerations

- The dataset includes personally identifiable information (PII) such as IDs, names, and dates of birth.
- Strict ethical considerations must be followed to protect customer privacy and comply with data protection standards.

### 3. Regulatory Compliance

- Financial companies must adhere to regulations such as GDPR, HIPAA, or other local financial data protection laws.
- Ensure transparent data processing, explicit consent for data collection, and compliance with regulatory requirements.

### 4. Imbalanced Datasets

- Financial data often exhibits imbalanced datasets, especially in terms of fraudulent and non-fraudulent transactions.
- Implement techniques like oversampling, undersampling, and advanced algorithms to address imbalanced datasets and improve model performance.

### 5. Fraud Detection

- In addition to predicting loan defaults, the model needs to incorporate fraud detection mechanisms to prevent financial losses.
- Consider incorporating fraud detection algorithms and techniques into the overall predictive model.

### 6. Data Quality and Integration

- Ensure the financial data used for analysis is of high quality, including consistency, accuracy, and completeness.
- Address challenges related to data integration from multiple sources, maintaining data integrity throughout the process.

## Key Performance Indicators (KPIs) and Metrics

A KPI is a measurable value that helps assess the performance and effectiveness of an organization, project, or individual. KPIs are specific metrics used to gauge progress toward goals, providing a clear indication of success or areas that may need improvement.
 
In the context of predicting the probability of loan default for a vehicle loan, several key performance indicators (KPIs) and measures of success are crucial to evaluate the effectiveness of your machine learning model. The choice of metrics depends on the specific goals and priorities of the financial institution. Here are some relevant KPIs and metrics:
 
### Accuracy:

- **Definition:** The proportion of correctly predicted instances (both default and non-default).
- **Importance:** Fundamental metric; consider in conjunction with other metrics due to potential class imbalance.

### Precision:

- **Definition:** The proportion of predicted defaults that are true defaults.
- **Importance:** Essential for minimizing false positives; a higher precision indicates fewer false positives.

### Recall (Sensitivity):

- **Definition:** The proportion of true defaults that are correctly predicted.
- **Importance:** Crucial for identifying most actual defaults; a higher recall indicates a lower number of false negatives.

### F1 Score:

- **Definition:** The harmonic means of precision and recall.
- **Importance:** Relevant for imbalanced cases; provides a balanced measure of precision and recall.

### Area Under the Receiver Operating Characteristic (ROC) Curve (AUC-ROC):

- **Definition:** Represents the trade-off between true positive rate and false positive rate at various thresholds.
- **Importance:** Provides a comprehensive summary of model performance; a higher AUC-ROC indicates better overall performance.

### Specificity:

- **Definition:** The proportion of non-default cases that are correctly predicted.
- **Importance:** Focuses on true negatives; helps minimize false alarms for likely repaid loans.

### Profitability Metrics:

- **Definition:** Metrics directly related to the financial impact of model predictions, considering gains and losses.
- **Importance:** Business goals may include net profit, return on investment, or other financial performance indicators.

# Deliverable 2

## S3 Bucket Setup
- **Bucket Creation:** Created an S3 bucket named "loandefaultpredictionuncc".
- **Folder Structure:** Organized project data within the bucket under the "Datasource" folder.

## AWS Athena Configuration
- **Table Creation:** Defined a table in Athena using DDL with predefined data attributes.
- **Time-based Analysis:** Conducted exploratory data analysis focusing on time-related patterns.

## Data Analysis
- **Credit History:** Analyzed credit history data, focusing on various aspects.
- **CNS Score Analysis:** Investigated the count of customers with specific CNS Scores.

## AWS Glue Operations
- **Crawlers Setup:** Configured crawlers to catalog and structure data stored in S3.
- **ETL Pipeline:** Designed a Glue ETL pipeline for data processing.

## Data Processing
- **Filtering Records:** Removed records with a disbursed amount below $15,000.
- **Removing Duplicates:** Eliminated duplicate entries from the dataset.
- **New Column Addition:** Introduced a column calculating "Available amount" (sanctioned - disbursed).

## QuickSight Visualization (Issue Encountered)
- **Access Issue:** Facing difficulties accessing QuickSight for data visualization.
    - *Troubleshooting:* Checked IAM permissions, S3 bucket access, and QuickSight configurations.

## Documentation
- **Readme File:** Compiled a readme file to document the setup steps and encountered issues.
    - *Format Details:* Included headings and subpoints for each stage of the project setup.

# Deliverable 3

1. **Installing Necessary Packages**
   - Installed required packages for data analysis and machine learning.

2. **Loading Data from S3 Bucket**
   - Retrieved data for evaluation and validation from an S3 bucket.

3. **Checking and Describing Train Dataset**
   - Examined the train dataset using head and dataset information to understand its structure.

4. **Test Dataset Information**
   - Checked the test dataset using head to gain insights into its contents.

5. **Handling Null Values**
   - Calculated the percentage of null values in both train and test datasets.
   - Used SimpleImputer to eliminate null values in columns.
   - Ensured no remaining null values in both datasets.

6. **Encoding Categorical Data**
   - Converted categorical objects into numerical values using label encoding.

7. **Date Columns Transformation**
   - Converted date columns into datetime objects for better analysis.

8. **Handling Outliers**
   - Detected and replaced outliers with median values to ensure data consistency.

9. **Feature Creation**
   - Calculated the age in both test and training datasets.

10. **Model Evaluation and Prediction**
    - Employed Random Forest techniques to evaluate the model and predict values.

11. **Evaluation Metrics**
    - Analyzed evaluation metrics for assessing model performance.

12. **Data Visualization**
    - Utilized various visualizations like heatmap, scatter plots, box plots, bar charts, etc., to analyze data relationships and patterns.

13. **Integration with QuickSight**
    - Provided a QuickSight link for accessing visualizations created.

14. **Chart Types Used**
    - Employed Line charts, Area charts, Pie charts, Tree maps, Vertical bar charts for visualization purposes.


# Deliverable 4

## AWS Cost Analysis and Optimization

## Overview

Analyzing the cost of running AWS resources involves several factors, including the type and quantity of resources used, data transfer costs, storage costs, and compute costs.

### Cost Considerations

- **S3 Bucket:**
  - Storage costs based on data stored and requests made (PUT, GET, etc.).
  
- **AWS Athena:**
  - Charges based on data scanned by queries.

- **Data Analysis:**
  - Compute resources usage for complex analysis (e.g., AWS Glue, Athena).
  
- **AWS Glue:**
  - Costs related to ETL jobs, processing time, and additional features.
  
- **Data Processing:**
  - Costs for processing resources and additional services used during data manipulation.
  
- **AWS SageMaker:**
  - Costs based on instances for model training/deployment, data storage, and other features.
  
- **Amazon QuickSight:**
  - Costs linked to SPICE capacity, author, and reader access.

### Cost Breakdown

| Service           | Monthly Cost (USD) | Usage                                 |
|-------------------|--------------------|---------------------------------------|
| Amazon S3         | $1.29              | Standard storage, requests, S3 Select  |
| AWS Athena        | $3.63              | Data scanned per query, total queries  |
| AWS Glue          | $6.60              | DPUs for Spark and Python Shell jobs  |
| Amazon SageMaker  | $27.54             | ML instance, Studio Notebook usage    |
| Amazon QuickSight | $31.40             | SPICE capacity, authors, readers      |

**Total Monthly Cost:** $70.46 USD

**Total 12 Months Cost:** $845.52 USD (including upfront costs)

## Cost Optimization Strategies

### S3 Bucket:
- Lifecycle Policies: Transition data to lower-cost storage classes based on access frequency.
- S3 Intelligent-Tiering: Automatically move objects between access tiers.

### AWS Athena:
- Partitioning and Data Organization.
- Optimize Queries to minimize data scanning.

### AWS Glue:
- Monitor DPU Usage and scale resources accordingly.
- Optimize ETL Jobs for efficiency.

### AWS SageMaker:
- Use Spot Instances for training jobs.
- Right-size Instances based on workload requirements.

### Amazon QuickSight:
- Monitor User Access and adjust permissions.
- Optimize Data Queries to reduce retrieval and processing costs.

Continuous monitoring using tools like AWS Cost Explorer and Trusted Advisor can provide further insights and tailored recommendations for cost optimization based on usage patterns.


