# Early Detection of Depression using R

## Project Overview
This project focuses on analyzing depression among adolescents using machine learning models, specifically **Random Forest** and **Logistic Regression**, to predict **major depressive episodes with severe impairment (mdeSI)**.

## Author
**Naman Singh**  
**NS1588**  
Semester 2
Course: *Applied Data Mining & Machine Learning*  
Instructor: *Dr. I-Ming Chiu*

## Project Repository
GitHub Repository: [Early Detection of Depression](https://github.com/namansingh2623/Early-Detection-of-Depression)

## Machine Learning Approach
We employed two primary classification models:
1. **Random Forest**
2. **Logistic Regression**

### Key Achievements
- Developed **Random Forest** and **Logistic Regression** models to predict **mdeSI** among adolescents.
- **Performance Metrics:**
  - **Random Forest:** Achieved an **AUC of 0.929** on test data.
  - **Logistic Regression:** Achieved an **AUC of 0.901** on test data.
- Identified significant predictors, including:
  - Gender
  - Income levels
  - Parental involvement
  - School experiences
- The findings support **early intervention strategies** in **clinical** and **educational settings**.

## Data and Methodology
### Data Mining Process
- Data preprocessing and feature engineering were conducted to extract the most relevant predictors.
- Implemented **Random Forest** and **Logistic Regression** models for classification.
- Evaluated model performance using **ROC-AUC**, **Precision-Recall**, and **Confusion Matrices**.

### Technologies Used
- **R** (for statistical modeling and data visualization)
- **Caret** (for machine learning model implementation)
- **ggplot2** (for visualization)
- **dplyr** (for data manipulation)

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/namansingh2623/Early-Detection-of-Depression.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Early-Detection-of-Depression
   ```
3. Install dependencies in R:
   ```r
   install.packages(c("caret", "ggplot2", "dplyr"))
   ```
4. Run the R Markdown analysis:
   ```r
   rmarkdown::render("SINGH_FinalProject.Rmd")
   ```

## Results
| Model              | AUC Score |
|-------------------|-----------|
| Random Forest     | 0.929     |
| Logistic Regression | 0.901     |

## Future Work
- Investigate **deep learning models** for improved accuracy.
- Enhance feature selection with **automated feature engineering**.
- Expand dataset coverage to include diverse demographics.
- Develop a **web-based tool** for use in mental health assessment.

## References
- Research studies on **adolescent depression**.
- Applications of **machine learning in mental health**.

## License
This project is open-source and available under the [MIT License](LICENSE).

---
*For more details, visit the GitHub repository:* [Early Detection of Depression](https://github.com/namansingh2623/Early-Detection-of-Depression)
