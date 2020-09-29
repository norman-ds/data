This folder contains the primary datasets used in Puntaminar artikels ["Die Zahl der Toten"](https://puntaminar.ch/de/2020/04/22/die-zahl-der-toten/) (April 2020) and ["Die Zahl der toten Senioren"](https://puntaminar.ch/de/2020/05/05/tote-senioren/) (Mai 2020).

The data will never be updated.

Below you'll find metadata.

## regionCH.csv

26 cantons und one country

- **Source(s) & Methodology**: [puntaminar gmbh](https://puntaminar.ch)
- **Last Modified**: April 2020
- **Contact Information**: [Norman](mailto:norman@puntaminar.ch)
- **Observations (Rows)**: Each row corresponds to a canton or country 
- **Variables (Columns)**:


| Header                    | Description                                            | Data Type                   |
| ------------------------- | ------------------------------------------------------ | --------------------------- |
| `geo`                     | geographical code                                      | text                        |
| `kanton`                  | cantonal abbreviation                                  | text                        |
| `kanton2`                 | name of canton                                         | text                        |


## ts-q-01.04.02.01.30.csv

Deaths recorded in 26 swiss cantons over 20 years

- **Source(s) & Methodology**: [Federal Statistical Office](https://www.bfs.admin.ch/bfs/en/home/statistics/health/state-health/mortality-causes-death.html)
- **Last Modified**: April 2020
- **Contact Information**: [Norman](mailto:norman@puntaminar.ch)
- **Observations (Rows)**: Each row corresponds to a death registration (anonymized) 
- **Variables (Columns)**:


| Header                    | Description                                            | Data Type                   |
| ------------------------- | ------------------------------------------------------ | --------------------------- |
| `time_period`             | year and calendar week                                 | text                        |
| `geo`                     | geographical code                                      | text                        |
| `age`                     | five year class                                        | text                        |
| `sex`                     | gender code                                            | text                        |
| `obs_value`               | number of cases                                        | text                        |
| `obs_status`              | the status of the observation.                         | text                        |


