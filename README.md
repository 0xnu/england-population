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

### Data Requirements

The analysis needs a CSV file with these columns:

+ `Year`: Year of population data (format: Mid-YYYY)
+ `Annual population change`: Numeric value of population change (with comma separators)

The data (Population estimates for England and Wales: mid-2024) is from [Office for National Statistics](https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/bulletins/populationestimatesforenglandandwales/mid2024).

### Run the Analysis

Click the `Run` button to run the individual cell of the [Jupyter Notebook](./england_population_change.ipynb).

### License

This project is licensed under the [Modified MIT License](./LICENSE).

### Copyright

(c) 2025 [Finbarrs Oketunji](https://finbarrs.eu). All Rights Reserved.