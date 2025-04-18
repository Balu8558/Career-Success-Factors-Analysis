# Career Success Factors Analysis

This project investigates the determinants of career success by analyzing the interplay between academic performance, practical experiences, and interpersonal skills. The analysis uses a dataset spanning university rankings, GPAs, internship records, skill scores, and career outcomes, employing exploratory data techniques, statistical hypothesis testing, and machine learning models.

## Project Overview

The project aims to identify and quantify the factors that most significantly influence career success among graduates, focusing on:

*   **Academic Influence:** The impact of university ranking, GPA, and standardized test scores.
*   **Experiential Learning:** The role of internships, projects, and certifications.
*   **Soft Skills & Networking:** The criticality of interpersonal skills and professional networking.
*   **Predictive Modeling:** Identifying the best models to capture the relationship between these variables and career success.

## Data Overview

The dataset includes features describing both academic and professional dimensions:

*   University Ranking
*   Academic Performance (University GPA, High School GPA, SAT scores)
*   Experiential Metrics (internships, projects, certifications)
*   Interpersonal and Professional Skills (soft skills, networking scores)
*   Career Outcomes (starting salary, job offers received)
*   Demographic Information (age, gender)

## Methodology

The analysis follows a systematic approach:

1.  **Exploratory Data Analysis (EDA):**
    *   Descriptive Statistics: Initial insights into data distributions.
    *   Visual Tools: Histograms, box plots, scatterplots, and correlation heatmaps.
2.  **Statistical Testing:**
    *   ANOVA: Assessed the statistical significance of differences in starting salaries and job offers across groups.
    *   Hypothesis Testing: Identified variables with a significant impact on career outcomes.
3.  **Predictive Modeling:**
    *   Logistic Regression: Analyzed the influence of predictors on salary outcomes.
    *   Random Forest: Provided deeper insights into variable importance and achieved higher accuracy.

## Key Findings

*   Higher GPAs and test scores are important but don't guarantee better job offers or higher starting salaries.
*   A positive correlation exists between the number of internships completed and job offers received.
*   The number of job offers significantly impacts starting salary.
*   The Random Forest model achieved an accuracy of 76.2%, identifying SAT scores, university ranking, and GPAs as influential factors.

## Recommendations

1.  **Enhance Practical Experience:** Encourage students to engage in internships and projects.
2.  **Strengthen Data Integrity:** Review data sources for anomalies and improve reliability.
3.  **Focus on Holistic Skill Development:** Integrate soft skills and networking into academic programs.
4.  **Model Advancement:** Explore more sophisticated models like neural networks.
5.  **Support for Lower-Ranked Institutions:** Provide additional resources to level the playing field.
6.  **Continuous Monitoring and Feedback:** Establish feedback mechanisms to track career outcomes.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit pull requests with your proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).
