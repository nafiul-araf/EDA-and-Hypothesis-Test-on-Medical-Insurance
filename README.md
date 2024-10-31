# Medical Insurance Data Analysis

## Project Description
This project aims to analyze a medical insurance dataset to uncover factors influencing insurance charges. By performing exploratory data analysis (EDA) and hypothesis testing, we gain insights into the impact of variables like age, BMI, and smoking status on charges. The findings can guide insurance companies in understanding risk profiles and optimizing pricing strategies.


### 2. Exploratory Data Analysis (EDA)
- **Aim**: To explore the distribution and relationships between key variables, such as sex, region, smoker status, BMI, and age, in relation to medical insurance charges.

#### A. Patient Demographics Distribution
  - **Objective**: To understand the distribution of patients by sex, region, and smoker status.
  - **Steps**:
    - Used `sns.countplot()` to visualize counts of male and female patients.
    - Created a count plot to show the distribution of patients across different regions.
    - Plotted smoker versus non-smoker counts.
    - **Insight**: These visualizations provide an initial understanding of the composition of the dataset, identifying the proportions of smokers, regions, and genders represented.

#### B. Proportion Analysis of Categorical Variables
  - **Objective**: To calculate and compare proportions within categorical features.
  - **Steps**:
    - Calculated the proportion of each category within 'sex', 'smoker', and 'region' columns.
    - **Insight**: This helps understand the relative size of each subgroup within the dataset.

#### C. Insurance Charges Analysis
  - **Objective**: To assess the total and subgroup-specific insurance charges.
  - **Steps**:
    - Calculated total charges and displayed the value in millions.
    - Grouped by `sex`, `smoker`, and `region` to calculate mean and total charges, as well as each subgroup's percentage of total charges.
    - **Insight**: This highlights how charges are distributed among different demographics and smoking habits, showing which groups contribute most to total insurance costs.

#### D. BMI Analysis
  - **Objective**: To explore BMI distribution across different demographics.
  - **Steps**:
    - Calculated total BMI across the dataset.
    - Grouped by `sex` and `smoker` status to calculate mean and total BMI, including the percentage of total BMI contributed by each group.
    - **Insight**: This provides insight into BMI patterns, helping assess health-related risk factors by subgroup.

#### E. Regression and Pairwise Relationships
  - **Objective**: To examine relationships between age, BMI, and other variables.
  - **Steps**:
    - Created regression plots of age vs. BMI, highlighting `sex`, `region`, and `smoker` status to see trends between age and BMI by group.
    - Used a joint plot to observe the joint distribution and correlation between age and BMI.
    - Created a pair plot to visualize pairwise relationships between variables with respect to sex.
    - **Insight**: These visualizations uncover patterns in age, BMI, and insurance features, which could point toward key factors impacting charges.
