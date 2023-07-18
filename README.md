# Analyzing International Debt Statistics

Project Goals
------------
* A SQL project where the amount of debt (in USD) owed by developing countries was analyzed using **_The World Bank_** dataset.
* This project aimed to answer three questions:
  * What is the total amount of debt that is owed by the countries listed in the dataset?
  * Which country owns the maximum amount of debt and what does that amount look like?
  * What is the average amount of debt owed by countries across different debt indicators?
 
File Structure
---------------
* Included in this repository is a .ipynb file that contains SQL code to query the dataset for international debt statistics. 

Results
------------
<p align="center">
  <img src="https://github.com/esaritepe/World_Debt/blob/main/screenshots/debt_total.png" />
</p>

* The total amount of debt owed by the listed countries is around $3079734500000.

<p align="center">
  <img src="https://github.com/esaritepe/World_Debt/blob/main/screenshots/debt_max.png" />
</p>

* China was determined to owe the maximum amount of debt, owing around $96218620836.

<p align="center">
  <img src="https://github.com/esaritepe/World_Debt/blob/main/screenshots/debt_indicators.png" />
</p>

* This query shows the average debt amounts by different indicators, ordered by average debt descending. The most common indicator is "Principal repayments on external debt, long-term (AMT, current US$)", with an average debt of $5904868401.
