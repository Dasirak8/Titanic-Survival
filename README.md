# Titanic-Survival
This project analyzes the Titanic passenger dataset to investigate whether survival chances were related to passenger class and age.

Titanic Survival by Class & Age
Project Overview
This project analyzes Titanic passenger data to understand how survival chances varied by passenger class and age. The business context is a shipbuilding company that wants to design future ships so that, in an emergency, all passengers have equal access to exits and safety equipment, regardless of ticket class or age group.

Business Goal
Management wants to answer two main questions:

Does survival rate have anything to do with passenger class?

How vulnerable are different age groups (children, youth & adults, seniors) in terms of survival?

The analysis is summarized in a Tableau dashboard that visualizes survival counts and survival rates by passenger class and age category.

Dataset
The project uses the classic Titanic passenger dataset (similar to the Kaggle “Titanic – Machine Learning from Disaster” data).

Key variables:

Survived: 0 = No, 1 = Yes

Pclass: Passenger class (1st, 2nd, 3rd)

Age: Passenger age in years

These fields are used to create visualizations of survival outcomes by class and age.

Meeting Summary (Task Documentation)
During the kick-off meeting with management:

Management explained that they suspect higher-class passengers had higher chances of survival and want to see if cabin layout or access to lifeboats might have contributed to this.

The analyst confirmed the goal: show how many people survived in each passenger class and compare survival rates between classes.

Management requested:

A bar chart showing, for each passenger class, how many people survived.

A bar chart showing, for each passenger class, the survival rate in percentage.

The analyst suggested adding age as a filter, so management can see whether differences between classes change for younger or older passengers. Management agreed.

Management then asked for an additional view by age categories (children, adults, seniors) to get a broader picture of survival patterns by age group.

Age categories were defined as:

Children: 0–14 years

Youth & adults: 15–64 years

Seniors: 65 years and over

This structure was documented as the analytical task for the project.

Analysis Steps (Conceptual)
The project follows these conceptual steps (no implementation details in this README):

Retrieve relevant fields (Survived, Pclass, Age) from the Titanic dataset.

Explore the data and identify missing values, especially missing ages.

Handle missing age values (e.g., by imputing with a central tendency measure) so every passenger can be placed into an age category.

Round ages to whole years to make age-based categories clearer.

Define and assign age categories: Children, Youth & Adults, Seniors.

Prepare an analysis dataset that includes survival status, passenger class, age, and age category, ready for visualization.

Visualizations (Tableau Dashboard)
The final Tableau dashboard focuses on the relationship between survival, class, and age:

Bar chart: Number of survivors by passenger class.

Bar chart: Survival rate (percentage) by passenger class.

Bar chart: Survival rate by passenger class and age category (children, youth & adults, seniors).

Filters: Age can be used as an interactive filter to explore how patterns change across different age ranges.

This dashboard allows management to quickly see whether higher classes had better survival chances and how age groups differ in survival outcomes.
