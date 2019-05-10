# ELT-Exercise


Extract

Nasdaq Healthcare company list (csv) from:
https://www.nasdaq.com/screening/companies-by-industry.aspx?industry=Health+Care

Clinical trials list and count by sponser (html) from:
https://clinicaltrials.gov/ct2/search/browse?brwse=spns_alpha_all

Transform

Created data frames from extracts and cleaned column titles and values.

Load

The final database where the data frames were uploaded as tables is sqlite. This database was chosen because sqlalchemy works easily
with pandas.
