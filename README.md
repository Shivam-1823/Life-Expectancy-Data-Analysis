# Life-Expectancy-Data-Analysis
Comprehensive descriptive and diagnostic analysis of life expectancy data across 193 countries (2000-2015). Includes Power BI dashboards and Python statistical analysis exploring factors like education, healthcare, and nutrition.

## 📊 Project Overview

This project presents a comprehensive analysis of global life expectancy data spanning from 2000 to 2015, covering 193 countries with 2,938 observations across 22 variables. The analysis combines both **descriptive** and **diagnostic** approaches to understand the factors influencing life expectancy worldwide.

### Key Findings
- **Global Average Life Expectancy**: 69.22 years
- **Range**: 36.3 to 89.0 years (52.7-year gap)
- **Development Gap**: 12.09 years between developed (79.20 avg) and developing countries (67.11 avg)
- **Strongest Predictor**: Education (Schooling) with correlation of 0.752
- **Success Stories**: Countries like Chile (85.0 years) demonstrate high performance regardless of development status

## 📁 Repository Structure

```
Life-Expectancy-Data-Analysis/
├── Life Expectancy Data.csv                    # Raw dataset (193 countries, 22 variables)
├── Life Expectancy Data Analysis.pptx          # Comprehensive presentation
├── Descriptive_Analysis_Dashboard...           # Power BI dashboard file
├── Life_Expectectency_Diagnostic_Anal...       # Python diagnostic analysis notebook
└── README.md                                   # Project documentation
```

## 🎯 Analysis Approaches

### Descriptive Analysis (Power BI)
**Question Answered**: *What happened?*

- Interactive dashboards with geographic visualizations
- Time-series trend analysis (2000-2015)
- Country comparisons and rankings
- Statistical summaries (mean, median, range)
- Development status comparisons

**Key Metrics Tracked**:
- Life expectancy by country and year
- BMI averages (38.32)
- HIV/AIDS prevalence (1.74 average)
- Adult mortality rates (164.80 average)

### Diagnostic Analysis (Python)
**Question Answered**: *Why did it happen?*

- Correlation matrix analysis
- Statistical significance testing
- Distribution analysis
- Missing value assessment
- Scatter plot visualizations

**Top Correlating Factors**:
1. **Education (Schooling)**: r = 0.752 - Strongest positive predictor
2. **Income Composition (HDI)**: Knowledge-based economies perform better
3. **BMI/Nutrition**: Adequate nutrition essential for longevity
4. **Adult Mortality**: Strong negative impact (high death rates reduce life expectancy)
5. **HIV/AIDS**: Epidemic diseases significantly impact populations

## 📈 Dataset Information

**Dataset Specifications**:
- **Countries**: 193
- **Time Period**: 2000-2015 (16 years)
- **Total Observations**: 2,938
- **Variables**: 22

**Key Variables**:
- Life expectancy (target variable)
- Adult Mortality
- Infant deaths & under-five deaths
- Alcohol consumption
- Health expenditure (% of GDP)
- Immunization coverage (Hepatitis B, Polio, Diphtheria)
- BMI
- HIV/AIDS prevalence
- GDP
- Population
- Education (years of schooling)
- Income composition of resources

## 🛠️ Technologies Used

- **Power BI**: Interactive dashboards and descriptive visualizations
- **Python**: Statistical analysis and diagnostic insights
  - Pandas for data manipulation
  - NumPy for numerical computations
  - Matplotlib/Seaborn for visualizations
  - SciPy/Statsmodels for statistical tests
- **Jupyter Notebook**: Analysis documentation

## 💡 Key Insights

1. **Education is the strongest predictor** of life expectancy (r=0.752), suggesting investment in education yields significant health benefits

2. **Development status matters**: 12-year gap between developed and developing countries, but both groups show consistent improvement

3. **Developing countries are progressing faster**: Closing the gap over time

4. **Healthcare access is crucial**: Immunization programs, primary healthcare, and adult mortality reduction are key factors

5. **Nutrition security**: Adequate nutrition (measured by BMI) is essential for higher life expectancy

6. **Success stories exist**: Countries like Chile, Costa Rica, and Cuba achieve high life expectancy despite being classified as developing

## 📊 Data-Driven Recommendations

Based on the analysis, we recommend:

### 1. Education Investment
- Universal primary and secondary education
- Adult literacy programs
- Health education initiatives
- Prioritize female education

### 2. Healthcare Systems
- Expand immunization programs
- Reduce adult mortality through preventive care
- Improve primary healthcare access
- Focus on disease prevention

### 3. Nutrition Security
- Prevent child malnutrition
- Implement food security policies
- Maternal health programs
- Nutrition education

## 🚀 Getting Started

### Prerequisites
- **Power BI Desktop** (for viewing dashboards)
- **Python 3.x** with Jupyter Notebook
- Required Python packages:
  ```bash
  pip install pandas numpy matplotlib seaborn scipy statsmodels
  ```

### Usage

1. **View Descriptive Analysis**:
   - Open the Power BI dashboard file (.pbix)
   - Explore interactive visualizations
   - Filter by country, year, or development status

2. **Run Diagnostic Analysis**:
   - Open the Jupyter Notebook
   - Run cells sequentially to reproduce statistical analysis
   - Modify parameters to explore different relationships

3. **Access Raw Data**:
   - CSV file available for custom analysis
   - 22 variables ready for further exploration

## 📝 Future Research Directions

- **Expand Timeline**: Include post-2015 data
- **Environmental Factors**: Add climate and pollution variables
- **Sub-National Analysis**: Regional disparities within countries
- **Causal Inference**: Advanced causal modeling
- **Machine Learning**: Predictive models for life expectancy
- **Longitudinal Studies**: Track specific cohorts over time
- **Policy Effectiveness**: Measure impact of specific interventions

## 👨‍💻 Author

**Shivam**
- GitHub: [@Shivam-1823](https://github.com/Shivam-1823)
- Email: shivamahlawat1823@gmail.com

## 📄 License

This project is available for educational and research purposes.

## 🙏 Acknowledgments

- Dataset source: World Health Organization (WHO) and United Nations data repositories
- Analysis framework inspired by global health research methodologies

---

*"Countries like Chile prove high performance is possible regardless of development status"* - Project Insight
