🏆 Predicting the Kolozsvár Student Days Winner with Machine Learning
A data science project by students, for a student-organized event

📚 Introduction
Kolozsvár Student Days is an annual competition composed of more than 50 diverse challenges. Teams—formed by groups of students test their knowledge, creativity, and teamwork in various events. While fun is an essential part of the experience, the competition is also serious: the team with the highest accumulated score at the end wins the event.

In this student-led machine learning (ML) project, we aim to create an application based on historical KMDZS data to:

Understand which factors (e.g. types of challenges, team characteristics, year of participation) most influence the total team score.

Cluster teams using unsupervised algorithms, helping identify naturally forming “skill tiers” or "clans."

Predict outcomes using supervised models (e.g. Decision Trees or Random Forests), such as whether a team might finish in the Top 5 or even win in the upcoming year.

💭 Why This Project Matters
Data from several past years of KMDZS has been collected in varied formats—some broken down by challenge, some as overall scores or rankings.

Through normalization, we unify this data across years into a consistent “long-form” database.

Exploratory Data Analysis (EDA) helps us understand patterns, score distributions, and correlations among challenges and teams.

Using feature engineering, we create informative new variables (like average performance per team, participation frequency, etc.).

Multiple ML models are tested and compared to determine which ones best predict team performance.

Finally, the analysis is used to offer insights and predictions about future competitions, which can also support KMDZS organizers in understanding which challenges most influence outcomes.

🔁 Project Pipeline
This is more than just statistical analysis—it's a complete end-to-end machine learning pipeline that turns raw event data into predictive insight.

Data Wrangling
→ Extract and unify embedded Excel files into a usable long-form dataset.

Data Normalization
→ Clean, fill missing values, and convert everything to a comparable numeric format.

EDA (Exploratory Data Analysis)
→ Visualize patterns and explore trends.

Feature Engineering
→ Create new variables (features) that improve model accuracy.

Modeling
→ Apply both supervised learning (e.g., classification) for prediction and unsupervised learning (e.g., clustering) for grouping similar teams.

Conclusion
→ Summarize findings and use predictions to simulate next year’s potential winning teams.

▶️ How to Run the Notebook
!!! IMPORTANT: Do not edit any code cells directly. Run everything in order for the data pipeline to work. !!!

Best way to execute:

In Jupyter Notebook or VS Code:

Click on Run → Run All Cells

This will execute all preprocessing and modeling steps from top to bottom.

Note: Ensure all required Python libraries (e.g., pandas, numpy, matplotlib, scikit-learn) are installed in your environment.
