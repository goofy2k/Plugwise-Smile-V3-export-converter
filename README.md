# Plugwise-Smile-V3-export-converter
takes Plugwise Smile V3 export files and converts to single table

C:\Users\Fred\Documents\CV ketel 2022\Plugwise\Plugwise-export-20221001-20230101

C:\Users\Fred\Documents\CV ketel 2022\Plugwise\Plugwise-export-20221221-20230121


Very dirty first version:  Smile2JSON V1.1.py

Name must be changed. Currently does not represent function

The script accepts old format (< end of 2022) and new format export files (Home_log_88ed2ae7e.csv)
Granularity is 1 hour and is not changed.
It reports gas and electricity cumulative data ("meterstanden") and puts nl_peak and nl_offpeak electricity data in SEPARATE COLUMNS


A more elegant way is to rely on xml parsing....  
