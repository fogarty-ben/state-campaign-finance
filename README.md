# State Campaign Finance

11 June 2019

Project by:
Ben Fogarty. 
Harris School of Public Policy, University of Chicago  

Andrew Friedman  
The College, University of Chicago. 

For the couse:  
CAPP 30310: Civic Techlonlogy  
Abhi Nemani  
Harris School of Public Policy 

## Requirements

This project was developed using Python 3.6.8 on MacOS Mojave 10.14.5. It is
deployed to Heroku with a Google Cloud SQL Postgres database supporting it.

The following packages are required:

| package | version |
| ------- | -------
| appnope | 0.1.0 |
| backcall | 0.1.0 |
| certifi | 2019.3.9 |
| decorator | 4.4.0 |
| dj-database-url | 0.5.0 |
| Django | 2.2.2 |
| django-heroku | 0.3.1 |
| gunicorn | 19.9.0 |
| ipython | 7.5.0 |
| ipython-genutils | 0.2.0 |
| jedi | 0.13.3 |
| parso | 0.4.0 |
| pexpect | 4.7.0 |
| pickleshare | 0.7.5 |
| prompt-toolkit | 2.0.9 |
| psycopg2 | 2.8.2 |
| ptyprocess | 0.6.0 |
| Pygments | 2.4.0 |
| pytz | 2019.1 |
| six | 1.12.0 |
| sqlparse | 0.3.0 |
| traitlets | 4.3.2 |
| wcwidth | 0.1.7 |
| whitenoise | 4.1.2 |

A conda environment containing all the necessary packages is available on
Anaconda Cloud by running the following command with Anaconda installed:

```
conda env create fogarty-ben/state_campaign_finance
```

Users must have database credentials and the secret key for their Django
instance save in their enviroment variables as DB_PASS and SECRET_KEY.

This repository is used for exclusively deployent, and the app is deployed to
Heroku from a private repository that is regularly updated from this repository.