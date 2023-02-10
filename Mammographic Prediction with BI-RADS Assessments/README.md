[![](/Mammographic%20Prediction%20with%20BI-RADS%20Assessments/Milestone_Project_3_Cover_Slide.png)](/Mammographic%20Prediction%20with%20BI-RADS%20Assessments/Milestone%20Project%203%20-%20Mammography%20Presentation.pdf)

> ### "Find a data set on a subject you care about and do something with it."  -- Sincerely your instructor

Those were the instructions for the third milestone project from the University of Wisconsin Data Science and Analytics Bootcamp, and this is truly a personal project.  You see, my wife is a breast cancer survivor.  This is a machine learning project that seeks to increase diagnostic precision in identifying malignant breast cancer tumors utilizing BI-RADS assessment data.

## Background

Before you can diagnose and treat a disease, you first must determine how you'll talk about it.  BI-RADS stands for Breast Imaging Reporting and Data System, and its [original goal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3099247/) was to agree upon the language of breast cancer.  What grew out of that lexicon was an image classification system used to diagnose malignant tumors.  

Prior to 2003, researchers in Nuremberg, Germany found that only 30% of breast biopsies were necessary.  They sought a means to increase their diagnostic precision.  This project uses the [Mammographic Mass Data Set](http://archive.ics.uci.edu/ml/datasets/mammographic+mass) provided by those researchers, and is located in the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php).  Following the links, you'll find the data set, an abstract, and a data dictionary.  

## Machine Learning Models

The project code is contained in a [Google Colaboratory](/Mammographic%20Prediction%20with%20BI-RADS%20Assessments/Milestone_Project_3_Mammography.ipynb) notebook.  It utilizes Python for data wrangling, exploratory data analysis, encoding, machine learning pipeline development, and hyperparameter tuning.  Prominent libraries include Pandas, Scikit Learn, Matplotlib, and Plotly.  Several machine learning models were developed to determine which produced the best precision.

## Presentation

The presentation begins by recounting a conversation my wife and I had with her surgeon, and happily ends with her cancer free with a 92% 5-year survival probability.  While we explore the data, I touch on the data set's origin and what BI-RADS are.  I explain the models tested and the methodology, before communicating the results.  Here is a pdf copy of the [presentation](/Mammographic%20Prediction%20with%20BI-RADS%20Assessments/Milestone%20Project%203%20-%20Mammography%20Presentation.pdf), or you can download the original [PowerPoint slides](Mammographic%20Prediction%20with%20BI-RADS%20Assessments/Milestone%20Project%203%20-%20Mammography%20Presentation.pptx) by clicking 'view raw' after following the link.

