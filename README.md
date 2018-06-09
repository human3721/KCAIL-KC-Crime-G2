## Introduction

This data shows the crime information within Kansas City, Missouri. The displayed information is the most current information from the data source as of the date of upload. The data source is dynamic and therefore constantly changing. Changes to the information may occur, as incident information is refined. While the Board of Police Commissioners of Kansas City, Missouri (Board) makes every effort to maintain and distribute accurate information, no warranties and/or representations of any kind are made regarding information, data or services provided. The Board is not responsible for misinterpretation of this information and makes no inference or judgment as to the relative safety to any particular area or neighborhood. In no event shall the Board be liable in any way to the users of this data. Users of this data shall hold the Board harmless in all matters and accounts arising from the use and/or accuracy of this data.


## Objectives:

Predict the monthly crime number 


## Data

The data for this project can be downloaded from https://data.kcmo.org:

* Dataset: 

| Name | Final? | Last\_Updated | Number\_Column | link |
| --- | --- | --- | --- | --- |
| KCPD Crime Data 2009 Final | Yes | March 7, 2018 | 24 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2009-Final/6efz-664k |
| KCPD Crime Data 2010 Final | Yes | March 7, 2018 | 24 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2010-Final/tk79-kf9y |
| KCPD Crime Data 2011 Final | Yes | March 7, 2018 | 24 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2011-Final/nt2f-uxvx |
| KCPD Crime Data 2012 Final | Yes | March 7, 2018 | 24 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2012-Final/csec-aghy |
| KCPD Crime Data 2013 Final | Yes | March 7, 2018 | 22 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2013-Final/m3xd-e7tp |
| KCPD Crime Data 2014 | No | March 7, 2018 | 24 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2014/yu5f-iqbp |
| KCPD Crime Data 2015 | No | March 7, 2018  | 26 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2015/kbzx-7ehe |
| KCPD Crime Data 2016 | No | March 7, 2018 | 26   | https://data.kcmo.org/Crime/KCPD-Crime-Data-2016/wbz8-pdv7 |
| KCPD Crime Data 2017 | No | March 5, 2018 | 24 | https://data.kcmo.org/Crime/KCPD-Crime-Data-2017/98is-shjt |


The variables included in this dataset are:


| Column Name | Description | Type |
| --- | --- | --- |
| Report\_No | Unique number assigned to a case, throughout the life of a case numerous reports can be written | Number |
| Reported\_Date | Date the offense was reported | Date &amp; Time |
| Reported\_Time | Time the offense was reported | Plain Text |
| From\_Date | Earliest date the incident could have occurred (From Date - To Date is the date range the incident could have occurred. If no range is used then the From Date is when the incident occurred and the From Time is the time the incident occurred) | Date &amp; Time |
| From\_Time | Earliest time the incident could have occurred | Plain Text |
| To\_Date | Latest date the incident could have occurred. (From Date - To Date is the date range the incident could have occurred. If no range is used then the From Date is when the incident occurred and the From Time is the time the incident occurred) | Date &amp; Time |
| To\_Time | Latest date the incident could have occurred | Plain Text |
| Offense | Offense code | Number |
| IBRS | National Incident Based Reporting System offense code | Plain Text |
| Description | Short description of the offense | Plain Text |
| Beat | Area where offense occurred | Number |
| Address | Cross streets of address where offense occurred | Plain Text |
| City |   | Plain Text |
| Zip Code |   | Plain Text |
| Rep\_Dist | Area where offense occurred | Plain Text |
| Area | Division the offense occurred in (Central, East, Metro, South, North, and Shoal Creek) | Plain Text |
| DVFlag | Indicates if it was a domestic violence offense | Plain Text |
| Invl\_No | On the report the involvement number of the persons listed ex; (Suspect # 1, Suspect #2 etc) | Number |
| Involvement | Person&#39;s involvement in the case (sus-suspect, vic-victim, arr-arrestee) | Plain Text |
| Race | • A – Asian • B – Black or African American • I – American Indian or Alaska Native • P – Native Hawaiian or Other Pacific Islander • U - Unknown • W – White | Plain Text |
| Sex | M-Male, F-Female, U- Unknown | Plain Text |
| Age | Age of victim/suspect/arrestee. If the victim/suspect/arrestee is a juvenile, the age is left blank | Number |
| Firearm Used Flag | Indicates if a firearm was used in the offense | Plain Text |
| Location |   | Location |



## Assignment

### Loading and preprocessing the data



### What is mean total number of crime taken per day/ month / season/year?
……

### What is the average daily activity pattern?
……

### Imputing missing values


### Are there differences in activity patterns between months/ seasons/ years?

### Are there differences in activity patterns between weekdays and weekends?


## Submitting your code


?
Go into our GitHub repository web page?


