# Healthcare-Patient-Profile-And-Expenditure-Report
## 📝 Project Description
The Healthcare Patient Profile and Expenditure Report is a comprehensive analytical tool designed to evaluate the intersection of clinical health markers and financial outcomes. By examining a diverse patient population, this dashboard identifies how lifestyle choices, pre-existing conditions, and demographic factors drive medical costs. The report serves as a strategic resource for identifying the primary catalysts of healthcare expenditure and tracking significant patient health trends.
## 📂 Data Source
The analysis is performed on a multi-dimensional dataset containing patient demographics, clinical histories, and billing information.

- **Key Variables**: BMI, HbA1c, Surgery/Transplant history, Hospital Tiering, and Total Charges.

- **Attributes**: 17 distinct data columns providing a holistic view of the patient journey.

- **Dataset**: <a href="https://github.com/saran-coding-core/Healthcare-Patient-Profile-And-Expenditure-Report/blob/main/healthcare%20dataset.xlsx">Healthcare Dataset</a>
## 📊 Key Metrics (KPIs)
The following metrics are highlighted via high-visibility cards:
- **Patient Count**: Total population size.
- **Average Age**: Mean age across the dataset.
- **Average BMI**: Population-wide Body Mass Index average.
- **Average HbA1c**: Mean blood glucose indicator.
- **Diabetes Rate**: Percentage of patients with a Diabetes diagnosis.
- **Obesity Rate**: Percentage of patients categorized as obese.
- **Total Charges**: Aggregate medical expenditure.
## 💡 Key Insights
- **Clinical Risk & Lifestyle Factors**
  - **Smoking & Oncology**: Smoking prevalence is consistent across groups; 21.5% of patients with a cancer history are smokers, compared to 20.8% in the non-cancer group.
  - **Transplant Analysis**: Patients with transplant histories account for 162 major surgeries and maintain a lower average HbA1c (5.2) compared to non-transplant patients (6.7).
 
- **Expenditure & Hospital Trends**
  - **Weight Status Impact**: Medical expenditure follows a clear hierarchy based on weight; costs are highest for patients with Obesity and decrease sequentially through Overweight, Normal Weight, and Under-weight categories.
  - **Diabetes Status**: Paradoxically, the highest average expenditure is observed in the Normal category, followed by patients with Diabetes and Pre-diabetes.
  - **Facility Tiers**: Average charges vary significantly across Hospital Tiers 1, 2, and 3, reflecting cost disparities based on facility level.
 
- **Statistical Correlations**
The data reveals varying degrees of correlation between patient age and health/financial outcomes:
  - **Age vs. Medical Charges**: 88.4% Correlation (The strongest driver of expenditure).
  - **Age vs. HbA1c**: 56.65% Correlation (Moderate relationship).
  - **Age vs. BMI**: 27.47% Correlation (Weakest relationship).
## 🖼️ Visualizations
- **Smoker Distribution**: Comparison across cancer history segments.
- **Surgical Volume**: Total major surgeries by transplant status.
- **Glycemic Trends**: Average HbA1c comparison for transplant vs. non-transplant patients.
- **Financial Weight Analysis**: Expenditure by Weight Status category.
- **Clinical Cost Analysis**: Expenditure by Diabetes Status.
- **Hospital Benchmarking**: Average charges across Hospital Tiers.
- **Aging & Health**: Correlation between Age and HbA1c.
- **Aging & Cost**: Correlation between Age and Medical Charges.
## 🛠️ Tools & Features
- **Excel Power Query**: Used for data cleaning and transformation.
- **Dynamic Slicers**: Allows users to filter report data by State and Hospital Tier.
- **Correlation Analysis**: Statistical modeling to determine relationships between variables.
