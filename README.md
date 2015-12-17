# Pardee Industry Survey Locator

The Pardee Industry Survey Locator was developed as a LAMP application several years ago by Tim Lewontin. The BU Libraries decided that we didn't want to continue to maintain the PISL as a separate application, but instead would create records for the industry surveys that could be loaded into Alma/Primo. 

The records were dumped from the MySQL database into three separate csv files:

*	contents.csv
*	source.csv
*	surveys.csv

A python script was created to create marcxml records from the csv files. This can be found in the iPython notebook

*	PardeeIndustrySurvey.ipynb










