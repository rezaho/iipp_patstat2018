[iipp]:https://iipp.epfl.ch/
[loading_tables]:https://github.com/rezaho/iipp_patstat2018/blob/master/BigQuery_Script.ipynb
[loading_tables_script]:https://github.com/rezaho/iipp_patstat2018/blob/master/BigQuery_Script.py
[changing_compression]:https://github.com/rezaho/iipp_patstat2018/blob/master/Changing_compression.ipynb
[google_sdk]:https://cloud.google.com/sdk/install


# Overview

This repository contains codes, which are necessary for loading, visualizing, and analyzing PatStat dataset. The codes will be added gradually. This is a project hosted by the [Chair of Innovation and IP Policy][iipp] at Colledge of Management, EPFL.

- For loading the data into Big Query tables, please refer to this [notebook: Loading BQ Tables][loading_tables] or [the python script][loading_tables_script]
- For changing the compression type of Patstat files to gzip, please refer to this [notebook: Changing Compression][changing_compression]


# Installation 

## Clone/ Download this repository

### Git

```bash
cd destination/path
git clone https://github.com/rezaho/iipp_patstat2018
````

### Download

1. Go to the [Open Patstat GitHub repository][GHOP]​
2. Click `Clone` or Download (top right)
3. Click `Download ZIP`

## Installing google big query library
Installing Big Query library is necessary for doing the introduced operations.
```bash
pip install --upgrade google-cloud-bigquery
````
# Google SDK
In case you have decided to use GCP bucket to upload your data and load them to Big Query, you need to install Google SDK for using `gsutil` module. Please, follow the instruction on [Google SDK][google_sdk].

