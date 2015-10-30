Create graphSON output from a tabular data file using an i2 Analysts Notebook import spec

Prereqs: Java 7

usage: java -Dprops=[name of properties file] -jar ProcessTabular.jar

Update the TabToGraph.properties file as follows:

apiURL=[URL of Bluemix Graph Data Store]

userId=[id for Bluemix Graph Data Store]

password=[password for Bluemix Graph Data store]

csv=[path to csv file]
  e.g. /Users/workspace/suspicious_phones.csv

ximp=[path to import spec] 
  e.g. /Users/workspace/MyNewImportSpec.ximp

output=[path for output json file] 
  e.g. /Users/workspace/outputNames1022.json

send=[true|false]
  value of "true" will import into indicated Bluemix Graph Data Store


