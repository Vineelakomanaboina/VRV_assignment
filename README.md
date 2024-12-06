# Log Analysis Script
## Overview
This Python script processes log files to analyze and extract key cybersecurity insights. It is designed for efficient log parsing, data analysis, and output generation.

## Features
Count Requests per IP Address: Displays the number of requests made by each IP address.
Identify Most Accessed Endpoint: Determines the endpoint with the highest access count.
Detect Suspicious Activity: Flags IPs with failed login attempts exceeding a configurable threshold.
CSV Output: Saves results to log_analysis_results.csv for easy review.
## Usage
Place the log file in the same directory as the script.
Run the script using:

python vrv_assignment.py
Results will be displayed in the terminal and saved in log_analysis_results.csv.
## Dependencies
Python 3.x
Libraries: None (uses standard Python libraries).
Log File Format
The script expects logs in a standard format like the provided sample.log.
