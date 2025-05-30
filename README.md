# Analyzing and Predicting Structural Damage Post-Earthquake in Kavrepalanchok, Nepal

![Alt text](https://github.com/Obika-Franklin/BuildingDamageAnalysis/blob/main/jade-koroliuk-PH9S5SfpV0E-unsplash%20(1).jpg)

This project addresses the critical challenge of predicting building damage from earthquakes, drawing lessons from the devastating 2015 Nepal earthquake. Focusing on the heavily impacted Kavrepalanchok district, the initiative involved meticulously collecting and organizing detailed building characteristics such as age, height, foundation, and roof types into a robust SQLite database. The core objective was to develop a predictive model capable of identifying buildings likely to suffer severe damage *before* an earthquake, thereby enabling proactive reinforcement and targeted aid distribution to enhance community resilience.

A significant hurdle encountered was the imbalanced nature of the dataset, where severely damaged buildings vastly outnumbered non-severely damaged ones, leading to initial model bias. To overcome this, two key strategies were employed: SMOTE (Synthetic Minority Oversampling Technique) was used to generate synthetic examples of non-severely damaged buildings, while Random Undersampling reduced the number of severely damaged building instances. By carefully tuning a Random Forest classifier and applying these balancing techniques, the project successfully developed a predictive tool that offers improved accuracy in identifying vulnerable structures, balancing the ability to detect true damage with reliable predictions.

In this project, we will work with data from Open Data Nepal. **You can get the datasets from Kaggle [here](https://www.kaggle.com/datasets/arashnic/earthquake-magnitude-damage-and-impact?select=mapping.csv).**

---
**Access the [Colab Notebook](https://colab.research.google.com/drive/1dK4KBLLCtoHXZnYBBLZ6-un66GuzyxKe?usp=sharing)**
