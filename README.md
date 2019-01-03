### Script for parsing nmap xml output to csv format
	This script is originally written by Didier Stevens and modified by Chintan Dave
### Changes Made
I have modified an existing Parsing script from Didier Stevens that parses the XML output from NMAP to CSV. It wasn't working properly for me and hence I updated the code to make it work. For best results parse the output with comma as a delimiter (or feel free to change excel's settings to use ; as a delimiter) - whatever works best for you.

### How to use
1. Normal usage to display results on the screen:
./nmap_xml_to_csv_parser.py test.xml
2. Change default delimiter(;) to , as follows:
./nmap_xml_to_csv_parser.py test.xml -s ,
3. Output to a csv file:
./nmap_xml_to_csv_parser.py -s , -o parsed_nmap_output_file.csv
