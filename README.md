# incident-analysis-ml
Implementation and comparison of various ML algorithms for classification of incident (text) data.

Based on the [Cross-industry standard process for data mining (CRISP-DM)](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining), the data was first understood from a business perspective and subsequently divided into a multi-class classification problem with four targets:
![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/methodology_area_cm.png)

Four different Machine Learning (ML) estimators were trained on the data and three different train/test split variations were compared:
![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/methodology_train_test_80.png)


![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/methodology_train_test_70_90.png)


An overview of the results for all different model and dataset variations is shown here:
![](https://github.com/DanishDahaka/incident-analysis-ml/blob/main/images/results_summary_graph.png)

As a key takeaway, an accuracy boost of up to **10 %** was gained through feeding the additional text data into the ML models.
Different train/test-splits did only slightly change the ML model accuracy.

Some files (e.g. accessing, joining and exploring the dataset / Latent Dirichlet Allocation (LDA)/ Word metrics) are not part of this repository.
If interested, feel free to ask about more info from these parts.
