# Preprocessing tasks
## Study project
#### Perform preprocessing tasks with the real datasets:

* **Task №1.** For each organization from main.csv, pull up revenue and the number of employees for 2020, 2021 and 2022:

  * calculate the delta by revenue and employees between 2022 and 2020;
  * sort the organizations in descending order of revenue. For organizations with the same revenue, sort by ascending ID;
  * if the organization doesn't have data on revenue or the number of employees for 2020 or 2022, then exclude them;
  * rename the columns in Russian.

* **Task №2.** Calculate the total revenue for 2022 by companies from individual companies from the list:

  * if some organizations don't have revenue for 2022, then take the latest available (for another year);
  * round the answer to the whole.

* **Task №3.** Upload organizations where the number of employees in 2020 is 15 or more:

  * if there is no employee data for 2020, then take 2019;
  * sort by ascending number of employees;
  * if the number of employees is the same, then the organizations should go in descending order of ID.

* **Task №4.** Find the TOP 10 organizations that paid the most taxes for the period 2019-2022 and at the same time paid tax for all 4 years:

  * the upload must contain an identifier, name, address, taxes by year and total tax;
  * sort by descending tax payment and by name in alphabetical order (for equal tax payments).


## Datasets

The datasets in **CSV** and **SQL** forms present data (with a single database of unique IDs) about coffee shops, restaurants, canteens and other places like that in Moscow: 

* [main.csv](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_1/main.csv) - the main information about companies;
* [net_property.csv](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_1/net_property.csv) - the designation of network enterprises;
* [seats_property.csv](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_1/seats_property.csv) - the number of seats;
* [type_property.csv](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_1/type_property.csv) - the information about specialization: canteen, snack bar, cafe, other;
* [indicators_db.sqlite3](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_1/indicators_db.sqlite3) - the SQL database with data on the revenue of enterprises and the number of employees.

## Results

* [Task №1](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_1/Task_1.ipynb);
* [Task №2](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_2/Task_2.ipynb);
* [Task №3](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_3/Task_3.ipynb);
* [Task №4](https://github.com/raent1/N_C_Projects/blob/main/preprocessing_pandas/folder_task_4/Task_4.ipynb).
