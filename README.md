# PPC extractors for Adobe Analytics
This is a set of examples how to get campaign data out from pay-per-click systems using Java.

## Metrics
- Impressions
- Clicks
- Cost

## Classifications
- Account Name
- Campaign Name
- Ad Set Name
- Ad Creative
- Ad Headline
- Ad Type
- Ad Clickthrough URL
- Ad Created date (only some systems)
- Ad Banner Size


## How ETL for Adobe Analytics work?
- Extract - using these examples
- Transform - you need to transform data into .tab or .csv files suitable for Adobe Analytics
- Load - import data into Adobe Analytics (using FTP or API)
- Schedule - use CRON or something similar to run this task regularly every night

## Prerequisites
- Unique click-through URL tagging for each creative (ad)
- Created Pay-per-click general Data Source in Adobe Analytics
- Created SAINT classification fields for you campaign eVar
- Generated access and developer tokens to PPC systems APIs


Wanna help? Reach me out at roman.gazarek@gmail.com
