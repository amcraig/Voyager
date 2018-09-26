# Voyager

### Maintained by: Alex Craig
***
Python module and Jupyter Notebook that pull from Google Sheets, submit jobs to remote host, and return dataframes for analysis
***
## How to:
* Get [OAuth2 Credentials](https://gspread.readthedocs.io/en/latest/oauth2.html)
* Access GSheet values via the gspread library

## TODO:
* Come to conclusion about accession libraries and begin to write a overencompassing module
* Create a 'production' notebook to implement the module backend

## I want the module to:
* Access GSheets and remote server without having to have too much knowledge of the imports
* Keep the production notebook clean in order to focus on the end-data analysis. Eliminate as much boilerplate code as possible
* Keep the remote cluster utilities 'locked down' i.e. must have a 'signed-okay file' in the directory to start, and limit user functionality in order to not screw up the cluster (foam pad the walls).
* Create archive. fetch, and clean utilities on chron schedules 
* Make sure the module is useful not in a jupyter notebook



