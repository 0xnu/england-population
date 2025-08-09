## england-population

[![Lint](https://github.com/0xnu/england-population/actions/workflows/lint.yaml/badge.svg)](https://github.com/0xnu/england-population/actions/workflows/lint.yaml)
[![Release](https://img.shields.io/github/release/0xnu/england-population.svg)](https://github.com/0xnu/england-population/releases/latest)
[![License](https://img.shields.io/badge/License-Modified_MIT-f5de53?&color=f5de53)](/LICENSE)

Data analysis and visualization of historical population trends in England.

### Install Dependencies

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install following

```sh
## Prerequisites
python3 -m venv .venv
source .venv/bin/activate
uv pip install -r requirements.txt
python3 -m pip install --upgrade pip
```

### Data Requirements (England Population)

The analysis needs a CSV file with these columns:

+ `Year`: Year of population data (format: Mid-YYYY)
+ `Annual population change`: Numeric value of population change (with comma separators)

The data (Population estimates for England and Wales: mid-2024) is from [Office for National Statistics](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/bulletins/populationestimatesforenglandandwales/mid2024).

### Data Requirements (EU and Non-EU Migration)

The dataset contains quarterly migration data from June 2012 to December 2024, tracking:

- Period: Quarterly period (e.g., YE Jun 12 to YE Dec 24 P)
- Non-EU+ migration: Number of migrants from non-EU countries (e.g., 57,000 in YE Jun 12 to 544,000 in YE Dec 24 P)
- EU+ migration: Number of migrants from EU countries (e.g., 187,000 in YE Jun 12 to -96,000 in YE Dec 24 P)
- British migration: Number of migrants from the UK (e.g., -83,000 in YE Jun 12 to -17,000 in YE Dec 24 P)
- Total migration: Total number of migrants (e.g., 162,000 in YE Jun 12 to 431,000 in YE Dec 24 P)

The data (Net migration by EU+, non-EU+ and British nationality) is from [Office for National Statistics](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/internationalmigration/bulletins/longterminternationalmigrationprovisional/yearendingdecember2024#long-term-net-migration).

### Run the Analysis

+ Click the `Run` button to run the individual cell of the [England Population - Jupyter Notebook](./england_population_change.ipynb).
+ Click the `Run` button to run the individual cell of the [EU and Non-EU Migration - Jupyter Notebook](./england_eu_noneu.ipynb).

### License

This project is licensed under the [Modified MIT License](./LICENSE).

### Copyright

(c) 2025 [Finbarrs Oketunji](https://finbarrs.eu). All Rights Reserved.