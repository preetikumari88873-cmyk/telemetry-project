# Telemetry Data Conversion
This Python project converts telemetry data from multiple JSON files into a unified output format.

## Features
- Reads multiple telemetry JSON files
- Maps fields correctly
- Converts ISO timestamps to milliseconds since epoch
- Produces a unified output JSON
- Includes unit tests for verification

## Files
main.py – main program  
data-1.json – sample input  
data-2.json – sample input  
data-result.json – expected output  

## How to Run
python main.py data-1.json data-2.json

## Output
The program generates a unified JSON output file.
