# ELT-Exercise


*Extract*

Nasdaq list of healthcare companies along with stock information (csv) from:
https://www.nasdaq.com/screening/companies-by-industry.aspx?industry=Health+Care

Clinical trials list and count by sponser/company (html) from:
https://clinicaltrials.gov/ct2/search/browse?brwse=spns_alpha_all

*Transform*

Created data frames from extracts and cleaned columns, titles, and values.

*Load*

The final database where the data frames were uploaded as tables was accomplished using sqlite. This database type was chosen because
sqlalchemy works easily with pandas.
