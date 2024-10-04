Project Description:

This project aims to create a system capable of predicting wind energy surpluses at least 24 hours in advance for specific regions. This predictive capability will allow us to notify customers and offer them the opportunity to opt-in for free energy slots.

Model Utilized:

We employed a Gradient Boosting Regressor model to forecast 24 hours into the future.

Dataset Information:

The dataset used is from Brighton, encompassing approximately 14 years of data.

Execution Instructions:

- Open the code file in Jupyter Notebook.
- Follow the step-by-step instructions provided in the notebook to execute the code cells sequentially.

Assumptions:

- Household Data Accuracy: The number of households is accurately reported as 114,479.
- Constant Consumption Rates: Average annual and hourly energy consumption rates per household are assumed to remain constant.
- Uniform Consumption: It is assumed that energy usage is evenly distributed throughout the day.
- Simultaneous Usage: Energy needs for 1,500 households are calculated on the basis that all households consume energy simultaneously.

References:

1. [Wind Energy Formula - GeeksforGeeks](https://www.geeksforgeeks.org/wind-energy-formula/)
2. [Brighton & Hove Housing Data](https://www.brighton-hove.gov.uk/sites/default/files/migrated/subject/inline/downloads/citystats/4_Housing.pdf#:~:text=In%20total%20there%20are%20118%2C953%20household%20spaces,in%20Brighton%20%26%20Hove%2C%20114%2C479%20have%20residents)