# Academy Data Gallery: data files

The CSV files behind the [Posit Academy](https://posit.co/products/enterprise/academy/) Data Gallery. The gallery pages, with previews and data dictionaries, are built into each Academy course site; this repo only hosts the files.

Every file is served by GitHub Pages at

```
https://rstudio.github.io/academy-data-gallery/<dataset>/data/<file>.csv     # data
https://rstudio.github.io/academy-data-gallery/<dataset>/assets/<file>.csv   # data dictionary
```

so you can read it straight from the URL. No download or upload is needed.

**R**

```r
covid <- readr::read_csv("https://rstudio.github.io/academy-data-gallery/covid/data/covid.csv")
```

**Python**

```python
import pandas as pd
covid = pd.read_csv("https://rstudio.github.io/academy-data-gallery/covid/data/covid.csv")
```

## Datasets

| Dataset | Data | Dictionary |
|---|---|---|
| Pew American Trends Panel (`american-trends-survey`) | [pew.csv](https://rstudio.github.io/academy-data-gallery/american-trends-survey/data/pew.csv) | [variables_pew.csv](https://rstudio.github.io/academy-data-gallery/american-trends-survey/assets/variables_pew.csv) |
| Auto Insurance Policies and Claims (`auto-insurance`) | [claims.csv](https://rstudio.github.io/academy-data-gallery/auto-insurance/data/claims.csv), [policies.csv](https://rstudio.github.io/academy-data-gallery/auto-insurance/data/policies.csv) | [variables_claims.csv](https://rstudio.github.io/academy-data-gallery/auto-insurance/assets/variables_claims.csv), [variables_policies.csv](https://rstudio.github.io/academy-data-gallery/auto-insurance/assets/variables_policies.csv) |
| Communicable Diseases in California (`ca-diseases`) | [ca_diseases.csv](https://rstudio.github.io/academy-data-gallery/ca-diseases/data/ca_diseases.csv), [ca_poverty.csv](https://rstudio.github.io/academy-data-gallery/ca-diseases/data/ca_poverty.csv) | [variables_ca.csv](https://rstudio.github.io/academy-data-gallery/ca-diseases/assets/variables_ca.csv) |
| COVID-19 Tracking (`covid`) | [covid_state_pop.csv](https://rstudio.github.io/academy-data-gallery/covid/data/covid_state_pop.csv), [covid.csv](https://rstudio.github.io/academy-data-gallery/covid/data/covid.csv) | [variables_covid_state_pop.csv](https://rstudio.github.io/academy-data-gallery/covid/assets/variables_covid_state_pop.csv), [variables_covid.csv](https://rstudio.github.io/academy-data-gallery/covid/assets/variables_covid.csv) |
| Credit Risk Modelling (`credit-risk`) | [credit_financial.csv](https://rstudio.github.io/academy-data-gallery/credit-risk/data/credit_financial.csv), [credit_personal.csv](https://rstudio.github.io/academy-data-gallery/credit-risk/data/credit_personal.csv) | [variables_credit-financial.csv](https://rstudio.github.io/academy-data-gallery/credit-risk/assets/variables_credit-financial.csv), [variables_credit-personal.csv](https://rstudio.github.io/academy-data-gallery/credit-risk/assets/variables_credit-personal.csv) |
| Electric Vehicles Sales (`electric-vehicle-sales`) | [cafe_data.csv](https://rstudio.github.io/academy-data-gallery/electric-vehicle-sales/data/cafe_data.csv), [ev_data.csv](https://rstudio.github.io/academy-data-gallery/electric-vehicle-sales/data/ev_data.csv) | [variables_ev_data.csv](https://rstudio.github.io/academy-data-gallery/electric-vehicle-sales/assets/variables_ev_data.csv) |
| IBM HR Analytics (`employee-attrition`) | [hr.csv](https://rstudio.github.io/academy-data-gallery/employee-attrition/data/hr.csv), [years.csv](https://rstudio.github.io/academy-data-gallery/employee-attrition/data/years.csv) | [variables_hr.csv](https://rstudio.github.io/academy-data-gallery/employee-attrition/assets/variables_hr.csv), [variables_years.csv](https://rstudio.github.io/academy-data-gallery/employee-attrition/assets/variables_years.csv) |
| Gas Prices and Sales (`gas-prices`) | [gas_prices_raw.csv](https://rstudio.github.io/academy-data-gallery/gas-prices/data/gas_prices_raw.csv), [gas_prices.csv](https://rstudio.github.io/academy-data-gallery/gas-prices/data/gas_prices.csv), [gas_sales.csv](https://rstudio.github.io/academy-data-gallery/gas-prices/data/gas_sales.csv) | [variables_gas_prices.csv](https://rstudio.github.io/academy-data-gallery/gas-prices/assets/variables_gas_prices.csv), [variables_gas_sales.csv](https://rstudio.github.io/academy-data-gallery/gas-prices/assets/variables_gas_sales.csv) |
| Hotel Booking Demand (`hotel-cancelations`) | [countries.csv](https://rstudio.github.io/academy-data-gallery/hotel-cancelations/data/countries.csv), [hotels.csv](https://rstudio.github.io/academy-data-gallery/hotel-cancelations/data/hotels.csv) | [variables_countries.csv](https://rstudio.github.io/academy-data-gallery/hotel-cancelations/assets/variables_countries.csv), [variables_hotels.csv](https://rstudio.github.io/academy-data-gallery/hotel-cancelations/assets/variables_hotels.csv) |
| Macroeconomic Indicators of Inflation (`macroeconomics`) | [macro.csv](https://rstudio.github.io/academy-data-gallery/macroeconomics/data/macro.csv) | [variables_macro.csv](https://rstudio.github.io/academy-data-gallery/macroeconomics/assets/variables_macro.csv) |
| Evictions in New York (NY) (`ny-evictions`) | [ny_eviction.csv](https://rstudio.github.io/academy-data-gallery/ny-evictions/data/ny_eviction.csv) | [variables_ny_eviction.csv](https://rstudio.github.io/academy-data-gallery/ny-evictions/assets/variables_ny_eviction.csv) |
| Drug Overdose and Injury Mortality (`overdose-injury`) | [injury.csv](https://rstudio.github.io/academy-data-gallery/overdose-injury/data/injury.csv), [overdose.csv](https://rstudio.github.io/academy-data-gallery/overdose-injury/data/overdose.csv), [pop.csv](https://rstudio.github.io/academy-data-gallery/overdose-injury/data/pop.csv) | [variables_injury.csv](https://rstudio.github.io/academy-data-gallery/overdose-injury/assets/variables_injury.csv), [variables_overdose.csv](https://rstudio.github.io/academy-data-gallery/overdose-injury/assets/variables_overdose.csv), [variables_pop.csv](https://rstudio.github.io/academy-data-gallery/overdose-injury/assets/variables_pop.csv) |
| Modification of Diet in Renal Disease (`renal-treatment`) | [mdrd.csv](https://rstudio.github.io/academy-data-gallery/renal-treatment/data/mdrd.csv), [supp.csv](https://rstudio.github.io/academy-data-gallery/renal-treatment/data/supp.csv) | [variables_mdrd.csv](https://rstudio.github.io/academy-data-gallery/renal-treatment/assets/variables_mdrd.csv), [variables_supp.csv](https://rstudio.github.io/academy-data-gallery/renal-treatment/assets/variables_supp.csv) |
| Soybean Yields (`soybean-yields`) | [soybase_checks.csv](https://rstudio.github.io/academy-data-gallery/soybean-yields/data/soybase_checks.csv), [soybase_lines.csv](https://rstudio.github.io/academy-data-gallery/soybean-yields/data/soybase_lines.csv), [soyin_checks.csv](https://rstudio.github.io/academy-data-gallery/soybean-yields/data/soyin_checks.csv), [soyin_lines.csv](https://rstudio.github.io/academy-data-gallery/soybean-yields/data/soyin_lines.csv) | [soybase_lines_dictionary.csv](https://rstudio.github.io/academy-data-gallery/soybean-yields/assets/soybase_lines_dictionary.csv), [soyin_lines_dictionary.csv](https://rstudio.github.io/academy-data-gallery/soybean-yields/assets/soyin_lines_dictionary.csv) |
| Stock Index and Sector Analysis (`stock-portfolios`) | [indexes.csv](https://rstudio.github.io/academy-data-gallery/stock-portfolios/data/indexes.csv), [sectors.csv](https://rstudio.github.io/academy-data-gallery/stock-portfolios/data/sectors.csv), [sp500.csv](https://rstudio.github.io/academy-data-gallery/stock-portfolios/data/sp500.csv) | [variables_indexes.csv](https://rstudio.github.io/academy-data-gallery/stock-portfolios/assets/variables_indexes.csv), [variables_sectors.csv](https://rstudio.github.io/academy-data-gallery/stock-portfolios/assets/variables_sectors.csv), [variables_sp500.csv](https://rstudio.github.io/academy-data-gallery/stock-portfolios/assets/variables_sp500.csv) |
| Walmart Sales (`walmart-sales`) | [items.csv](https://rstudio.github.io/academy-data-gallery/walmart-sales/data/items.csv), [sales_sample.csv](https://rstudio.github.io/academy-data-gallery/walmart-sales/data/sales_sample.csv) | [variables_items.csv](https://rstudio.github.io/academy-data-gallery/walmart-sales/assets/variables_items.csv), [variables_sales_sample.csv](https://rstudio.github.io/academy-data-gallery/walmart-sales/assets/variables_sales_sample.csv) |

## Updating

Add or replace files under `<dataset>/data/` and `<dataset>/assets/`, then push to `main`; Pages redeploys automatically. Keep each file under 50 MB. The gallery pages that describe these files live in [`rstudio/academyTutorials`](https://github.com/rstudio/academyTutorials) under `shared_resources/data-gallery/`, so a new dataset needs a page there too.

These files were previously served from the retired `rsacdn.link` CDN (`/milestones/internal/<dataset>/...`); the folder layout is unchanged.
