## Predicting student admissions using Keras

In this notebook, student admissions is predicted with neural networks in [Keras](https://pypi.org/project/Keras/). The students admissions to graduate school at UCLA is based on three pieces of data:

* GRE Scores (Test)
* GPA Scores (Grades)
* Class rank (1-4)

![2D plot admissions](ucla_stu_admission.png)

### Data

The dataset originally came from here: http://www.ats.ucla.edu/. The small dataset has total 400 entries, each having 4 columns: admit, gre, gpa, rank.
