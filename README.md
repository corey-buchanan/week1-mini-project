# Week 1 Mini-Project
I'm using Chat GPT to give me prompts for 'mini-projects' that I can use to learn Clojure.

## Chat GPT specs:

Week 1 Mini-Project: CSV File Converter

Description:
Create a command-line program in Clojure that allows users to convert CSV files between different formats. Your program should be able to perform the following tasks:

CSV to JSON: Convert a CSV file to JSON format.
JSON to CSV: Convert a JSON file back to CSV format.
Filtering: Allow users to specify filters to select specific rows or columns from the CSV file during conversion.

Example Usage:
```
$ clojure csv-converter.clj csv-to-json input.csv output.json
$ clojure csv-converter.clj json-to-csv input.json output.csv
$ clojure csv-converter.clj filter input.csv filtered.csv --filter "column_name = 'value'"
```

This project will help you practice working with file I/O, data transformation, and command-line argument parsing in Clojure while providing a useful tool for data manipulation.

## Implementation notes:

// TODO - Fill out this section with command line usage for this program as implemented
