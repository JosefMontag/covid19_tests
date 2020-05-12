# covid19_tests
## International Data on SARS-CoV-2 Testing Volume (by date and country)

### About this data

"**Test! Test! Test!**" is WHO's core prescription to treat the SARS-CoV-2 pandemic.

Data on testing is critical to our understanding of dynamics of the SARS-CoV-2 pandemic and the responses of individual governments and their efficacy.

This is a **public repository for international data on SARS-CoV-2 testing volumes** with the goal to provide analysis-ready data for analyses of the pandemic and testing policies.

### An important update (switch to Worldometer's data)

Because Worldometer recently started to publish daily data on SARS-CoV-2 testing volumes (together with data on cases and deaths) and it covers almost all countries, I begun to log this data. We have interupted our previous efforts.

Thus, starting **from April 8, 2020**: 

* Every day I save the previous day's table from www.worldometers.info/coronavirus. 
* I put the daily tables together, drop aggregate statistics (World, continents), and add dates and ISO country codes. 
* The resulting analysis-ready datasets are stored in folder *Worldometer_COVID_data* and will be updated weekly. 
* The raw data tables from Worldometer are stored under subfolder *Raw_data*.

### Updates and merging with other datasets

We will be posting snapshots of this data in the long (panel) form. Each country-day observation is identified using standard ISO 3166 country codes and the data can thus be easily merged with other relevant cross-country datasets.

### Previous data on SARS-CoV-2 testin volumes

The previous data on covid tests remain unchanged but are not being updated as of now. This data can be merged with Worldometer's data using date and ISO3 country codes (in both datasets). We checked and Worldometer's data and our earlier data on testing volumes are consistent. However, both datasets should to be checked for consistency before conducting any analysis.

We continue scraping some data automatically (the files are available upon request) and manually in our Google sheet at bit.ly/covid-tests-data. This data can be used to check for consitency between Worldometer's data and the sources that we identified and document in the Google sheet.

### Maintainer

This data repository is maintained by 

Josef Montag, PhD    
Department of Economics  
Faculty of Law  
Charles University
josef.montag@gmail.com
sites.google.com/site/josefmontag

This data gathering effort was originally co-initiated by Petr Barton of Natland Investment Group.
