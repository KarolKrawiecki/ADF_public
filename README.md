# ADF_public

Public repo for Analyzing Digital Footprints (course in the BAM MSc, RSM)

Examples in this repo:

## `API_Kiva`

How to collect data using the Kiva API, and how to process the results.

- `aux_functions.R` contains example helper functions (`f_get...`) that you can use to extract specific fields from the response object
- `how_to_filter_by_riskRating.R` - exactly what the filename says
- `how_to_get_MoreThan100LoanIDs.R` - exactly what the filename says
- `loan_id`: how to get information about a specific loan id
- `loans_filter`: how to get ids of loans that meet specific criteria and then loop through all the loan IDs and get additional details for each of them.
- `steps_to_collect_data.R` shows how to structure the data collection file

## `data_outside_repo`

How to use environment variables to deal with situations when data is outside the repo and when you do not want to share all the original observations.

## `how_to_Rmd`

How to use advanced R Markdown functionalities that enable reproducible reports.
