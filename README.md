# border-crossing-analysis
This is my attempt to sort CSV file using Python

# Problem 
The Bureau of Transportation Statistics regularly makes available data on the number of vehicles, equipment, passengers and pedestrians crossing into the United States by land.

For this challenge, I will calculate the total number of times vehicles, equipment, passengers and pedestrians cross the U.S.-Canadian and U.S.-Mexican borders each month. I will also calculate running monthly average of total number of crossings for that type of crossing and border.

# Language and Libraries used 
csv

argparse

operator

datetime

itertools

math
# How to run 
Run the run.sh bash file, which will call my border_crossing_statistics.py script.
Also specify the input and output file name. 

example - python3 src/border_crossing_statistics.py --input input/Border_Crossing_Entry_Data.csv --output output/report.csv
