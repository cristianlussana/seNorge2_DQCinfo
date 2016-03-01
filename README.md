seNorge2\_DQCinfo
==================
seNorge2 data quality control information

Blacklists
-----------
List of station identifiers (MET Norway codes) NOT to be used for spatial interpolation purposes
file name format: seNorge2\_VARIABLE\_blacklist.txt
VARIABLE = PREC1h, PREC1d
PREC1h file is valid for hourly and 3-hourly variables
PREC1d file is valid for daily variables

Suspect observations
--------------------
List of specific measurements NOT to be used for spatial interpolation purposes
The file header is:
"stnr;year;month;day;hour;value;"
where:
stnr: station number
year;month;day;hour: date and time of the suspect observation
value: suspect value. Note: if the observation in the MET Norway database is different for the specified value, then it is used in spatial interpolation
