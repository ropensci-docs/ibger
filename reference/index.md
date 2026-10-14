# Package index

## Retrieve data

Main functions to query the IBGE API.

- [`ibge_variables()`](https://docs.ropensci.org/ibger/reference/ibge_variables.md)
  : Get variable data from an aggregate
- [`ibge_aggregates()`](https://docs.ropensci.org/ibger/reference/ibge_aggregates.md)
  : List IBGE aggregates

## Explore metadata

Discover available aggregates, variables, periods, localities, and
subjects.

- [`ibge_metadata()`](https://docs.ropensci.org/ibger/reference/ibge_metadata.md)
  : Metadata for an aggregate
- [`ibge_periods()`](https://docs.ropensci.org/ibger/reference/ibge_periods.md)
  : Periods for an aggregate
- [`ibge_localities()`](https://docs.ropensci.org/ibger/reference/ibge_localities.md)
  : Localities for an aggregate
- [`ibge_subjects()`](https://docs.ropensci.org/ibger/reference/ibge_subjects.md)
  : IBGE subject codes lookup

## Survey catalog

Browse IBGE surveys and their institutional metadata via the Metadata
API (v2).

- [`ibge_surveys()`](https://docs.ropensci.org/ibger/reference/ibge_surveys.md)
  : List IBGE surveys with metadata
- [`ibge_survey_periods()`](https://docs.ropensci.org/ibger/reference/ibge_survey_periods.md)
  : List periods with metadata for a survey
- [`ibge_survey_metadata()`](https://docs.ropensci.org/ibger/reference/ibge_survey_metadata.md)
  : Get survey metadata for a specific period

## Utilities

Helpers and cache management.

- [`parse_ibge_value()`](https://docs.ropensci.org/ibger/reference/parse_ibge_value.md)
  : Parse IBGE value column
- [`ibge_clear_cache()`](https://docs.ropensci.org/ibger/reference/ibge_clear_cache.md)
  : Clear metadata cache
- [`fetch_sidra_url()`](https://docs.ropensci.org/ibger/reference/fetch_sidra_url.md)
  : Fetch data from a SIDRA API URL
- [`parse_sidra_url()`](https://docs.ropensci.org/ibger/reference/parse_sidra_url.md)
  : Parse a SIDRA API URL into ibger parameters
- [`ibge_explorer()`](https://docs.ropensci.org/ibger/reference/ibge_explorer.md)
  : Interactive aggregate explorer
