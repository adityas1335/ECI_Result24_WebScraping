# ECI_Result24_WebScraping

## Overview
This project, **ECI_Result24_WebScraping**, is designed to scrape and extract election results from the Election Commission of India (ECI) website. The extracted data includes candidate-wise and constituency-wise results and is saved into a CSV file for further analysis.

## Version
- **V1**: Version 1.0

## Project Components
The project comprises two main modules:
1. **Candidate_Constituencywise_Result (CCR)**
2. **Constituencywise_ResultV1 (CR)**

## Features
The project is based on the following functionalities:

1. **Webpage Request and Parsing**
   - Requests the content of a specified ECI results webpage.
   - Parses the webpage using BeautifulSoup to extract relevant information.

2. **State and Constituency Extraction**
   - Extracts the state and parliamentary constituency name from the parsed HTML content.
   - Processes and cleans the extracted names for accuracy.

3. **Table Data Extraction**
   - Locates the table containing election results within the webpage.
   - Iterates through the table rows to gather details of each candidate, including their vote counts.

4. **Data Parsing and Summation**
   - Parses and converts vote counts from strings to integers or floats.
   - Calculates the total votes for each candidate and sums up the total votes across all candidates.

5. **Appending Total Votes Sum**
   - Appends the sum of total votes as a new column to each row of extracted data for additional context.

6. **CSV File Creation**
   - Saves the extracted and processed data into a CSV file.
   - The CSV file is named based on the state and constituency for easy identification.
