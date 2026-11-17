# Member-Insights-Analytics


Note:
1.  As noted in the dataset documentation, the author recommends excluding the "duration" attribute when building a realistic predictive model. Duration is only known once a call has ended, and by that point the outcome is effectively known as well, so the model would be using information that wouldn't be available at prediction time. Including it can be useful for benchmarking, but it should be dropped if the goal is a model that predicts the outcome before a call is made.
2.  Missing attributes are labeled as "unknown" from the original dataset.
3. The project data files are listed in .gitignore, so they are not tracked or pushed to the repository. This mimics how sensitive data would be handled in a real setting, where raw data is kept private and stays out of version control. The link for the dataset has been provided on the citation.

Tools & Technologies:
- Google Colab
- 

Citation:
Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306