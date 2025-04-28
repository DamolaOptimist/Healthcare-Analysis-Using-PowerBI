# Healthcare Patient Analysis Dashboard
## Table of contents
  - [Project Overview](project-overview)
  - [Project Objectives](project-objectives)
  - [Dataset](dataset)
  - [Technologies Used](technologies-used)
  - [Key Insights](key-insights)
### Project Overview
This project presents a Power BI dashboard built to analyze patient care records across 10 major U.S. hospitals.
The analysis is based on a dataset of 55,500 unique patient records, capturing key aspects such as admissions, medical conditions, medications, insurance providers, treatment costs, and patient outcomes. The goal of this project is to uncover insights that can:
  - Drive better healthcare decisions
  - Optimize treatment costs
  - Improve patient outcomes
  - Help stakeholders make data-informed decisions
### Project Objectives
- What are the most common age groups, genders, and blood types among patients? Are certain groups being admitted more often than others?
- Which medical conditions are diagnosed the most, and do they affect certain groups of people more than others?
- How long do patients typically stay in the hospital for different conditions? Does this vary depending on the hospital or type of admission (emergency, urgent, or planned)?
- How much does treatment usually cost for each condition? Are there big differences in costs between hospitals or insurance providers?
- Which hospitals are treating the most patients, and how do they compare in terms of patient outcomes, like test results?
- What medications are most often prescribed for each condition? Are they being used consistently across hospitals?
- How are patients admitted - mostly through emergency, urgent, or planned admissions - and how does that impact the length of stay or treatment costs?
- Which insurance companies are covering the most patients, and how does that relate to treatment costs and patient outcomes?
### Dataset
1. The data was provided by Onyx Data for a challenge on linkedIn
2. The dataset was a clean data so no cleaning was required
### Technologies Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
### Key Insights
1. Patient Demographics
   - Age Groups:
        - Seniors (60+) account for the largest portion of hospital admissions, followed closely by Adults (40–59).
        - Young Adults (20–39) and Teenagers (13–19) represent a smaller share of admissions.
    - Gender Distribution:
       - 50% of patients are Female, 40% are Male, and 10% identify as Non-binary.
     - Blood Types:
         - The most common blood types among patients are B+, O+, and A+.
         - Certain blood types (e.g., A+, O+) are associated with a higher incidence of chronic conditions like Diabetes and Hypertension.

2. Medical Conditions Diagnosed
   - Top Diagnosed Conditions:
        - Diabetes and Hypertension are the two most prevalent medical conditions among patients.
        - Obesity also shows a strong correlation with hospital admissions.

    - Demographic Impact:
        - Seniors and adults are more prone to chronic conditions such as Diabetes, Hypertension, and Arthritis.
        - Teenagers show relatively lower cases of chronic conditions.

3. Hospital Length of Stay (LOS)
     - The average Length of Stay (LOS) across conditions is around 15.5 days.
     - LOS by condition:
          - Hypertension patients: ~15.64 days
          - Arthritis patients: ~15.56 days
          - Asthma patients: ~15.39 days

     - Minor variations exist across conditions, but no extreme outliers were found.

4. Treatment Costs
     - Average Billing Amount per Patient: ~$25,540.
     - Total Billing Amount Across Dataset: ~$1.42 billion.
     - Hospital Cost Variation:
          - Houston Methodist Hospital had the highest billing amounts, significantly higher than other hospitals.
     - Insurance Cost Variation:
          - Billing amounts vary slightly by insurance provider.
          - Cigna and UnitedHealthcare patients generally incur slightly higher treatment costs compared to Medicare patients.

5. Hospital Patient Volume and Outcomes
      - Top 3 Hospitals by Billing Amount:
           1. Houston Methodist Hospital
           2. Johns Hopkins Hospital
           3. UCLA Medical Center

      - Patient Outcomes (Test Results):
          - Majority of test results were Abnormal (~30,525 cases).
          - Normal results were relatively lower (~5,550 cases), suggesting the patient population is quite ill at admission.
          - Certain hospitals like Mayo Clinic and Cedars-Sinai Medical Center had a higher proportion of normal outcomes.

6. Medication Usage
     - Top Prescribed Medications:
       - Ibuprofen, Aspirin, Penicillin, Paracetamol, and Lipitor are the most frequently prescribed medications.
     - Condition-specific Prescriptions:
       - Aspirin and Ibuprofen are heavily prescribed for Diabetes and Hypertension patients.
       - Lipitor is commonly prescribed across multiple chronic conditions.

7. Admission Types
    - Admissions are evenly split between:
      - Elective (~33.61%)
      - Emergency (~32.92%)
      - Urgent (~33.47%)

    - Impact on LOS and Cost:
       - Emergency admissions are correlated with slightly longer LOS and higher treatment costs.
       - Planned (elective) admissions are generally more cost-controlled and efficient.

8. Insurance Provider Trends
   - Top Insurance Providers by Coverage:
        1. Medicare
        2. UnitedHealthcare
        3. Cigna
        4. Aetna

   - Impact on Costs and Outcomes:
       - Patients covered by Medicare and Aetna tended to have slightly lower average billing amounts compared to those with Cigna.
       - Outcome patterns (test results) vary slightly across insurers but not drastically.
