# Claims Classification

**Note:** This is the TikTok workplace scenario that I chose to work on while completing the courses. The story, all names, characters, and incidents portrayed in this project are **fictitious**. No identification with actual persons (living or deceased) is intended or should be inferred. And, the data shared in this project has been created for pedagogical purposes.

## :label: Table of Contents (TOC)
- [File/Code Structure](#open_file_folder-filecode-structure)
- [Project Description](#memo-project-description)
- [Data Source](#mag_right-data-source)
- [Summary](#open_book-summary)
- [Result](#dart-result)
- [Tech Stack](#hammer_and_wrench-tech-stack)

---

## :open_file_folder: File/Code Structure

```bash
├── data                                                            # data folder
│   └── tiktok_dataset.csv
├── executive_summaries                                             # executive summaries folder
│   ├── 2_executive_summary-preliminary_data_investigation.pdf          # preliminary data investigation
│   ├── 3_executive_summary-eda.pdf                                     # EDA
│   ├── 4_executive_summary-statistical_testing.pdf                     # statistical testing
│   ├── 5_executive_summary-regression_modeling.pdf                     # regression modeling
│   └── 6_executive_summary-final_model_outcome.pdf                     # final model outcome
├── imgs                                                            # image folder
│   └── tiktok_data_dictionary.png
├── 1_project_proposal.pdf                                          # project proposal
├── 2_preliminary_data_investigation.ipynb                          # jupyter notebook for preliminary data investigation
├── 3_EDA.ipynb                                                     # jupyter notebook for exploratory data analysis (EDA)
├── 4_hypothesis_testing.ipynb                                      # jupyter notebook for hypothesis testing
├── 5_regression_modeling.ipynb                                     # jupyter notebook for regression model
├── 6_final_model.ipynb                                             # jupyter notebook for final model
├── README.md
└── requirements.txt                                                # required libraries (environment)
```

[Back to TOC](#label-table-of-contents-toc)

## :memo: Project Description

**Goal:** The TikTok data team is developing a machine learning model for classifying claims made in videos submitted to the platform.

**Background**: At TikTok, our mission is to inspire creativity and bring joy. Our employees lead with curiosity and move at the speed of culture. Combined with our company's flat structure, you'll be given dynamic opportunities to make a real impact on a rapidly expanding company and grow your career.

TikTok users have the ability to report videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. This process generates a large number of user reports that are difficult to address quickly. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.

[Back to TOC](#label-table-of-contents-toc)

## :mag_right: Data Sources

Data is provided by the course.

[Back to TOC](#label-table-of-contents-toc)

## :open_book: Summary

This project consists of 6 parts:

1. Project Proposal: Organize project tasks into milestones, classify tasks using the PACE (Plan, Analyze, Construct, Execute) workflow, and identify relevant stakeholders.
    - Deliverables: Project proposal
2. Preliminary Data Investigation: Inspect, organize, and prepare the data for analysis. Summarize findings in executive summary
    - Deliverables: Preliminary data investigation in Jupyter Notebook, executive summary
3. Exploratory Data Analysis: Explore, analyze, and visualize data. Use Tableau to create visuals and executive summary to help non-technical stakeholders engage and interact with the data.
    - Deliverables: EDA in Jupyter Notebook, visualizations in Tableau, executive summary
4. Hypothesis Testing: Conduct hypothesis testing to analyze the relationship between video_view_count and verified_status.
    - Deliverables: Hypothesis testing in Jupyter Notebook, executive summary
5. Regression Model: Build a logistic regression model to investigate how variables are related to the `verified_status` variable.
    - Deliverables: Regression modeling in Jupyter Notebook, executive summary
6. Final Model: Build a Random Forest model and XGBoost model to classify if a video contains a claim or an opinion.
    - Deliverables: Final model in Jupyter Notebook, executive summary

[Back to TOC](#label-table-of-contents-toc)

## :dart: Results

The final machine learning model built using random forest performed exceptionally well. It has a 99% accuracy and 99% recall on the test set. The model predicted opinions perfectly and only misclassified 18 claims videos as opinion.

[Back to TOC](#label-table-of-contents-toc)

## :hammer_and_wrench: Tech Stack

Language: Python

Libraries: NumPy, pandas, Matplotlib, Seaborn, SciPy, scikit-learn, xgboost

Tool: Jupyter Lab, Tableau

[Back to TOC](#label-table-of-contents-toc)
# tiktok-claim-classify
