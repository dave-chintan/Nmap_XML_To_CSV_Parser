### Script for parsing nmap xml output to csv format
	This script is originate by Didier Stevens and modified by Chintan Dave
### Version
I have modified an existing Parsing script from Didier Stevens that parses the XML output from NMAP to CSV. It wasn't working properly for me and hence I made some changes.

### How to use
1. Normal usage for display result
./nmap-xml-script-output-modify.py test.xml
2. Change default delimiter(;) to ,
./nmap-xml-script-output-modify.py test.xml -s ,
3. Output to test.csv
./nmap-xml-script-output-modify.py test.xml -s , -o test.csv
