This Python script processes a CSV file, adjusting the text in the first seven columns to title case, where the initial letter of each word is capitalised. It utilises Python's in-built csv module for reading and writing CSV files.
Process:

The script reads an input CSV file, example "companies.csv".
It modifies the text in columns A to G, changing them to title case.
The adjusted data is saved to a new CSV file, appending "_proper_case" to the original file's name.
A confirmation message displays the name of the new file.

Use Case:
Imagine a company in the UK has a database of client names and addresses in a CSV file. Over time, due to various data entry methods, the casing of the names and addresses has become inconsistent. Some entries are in all caps, some in lowercase, and others mixed. Before sending out a formal communication or report, the company wants to ensure all names and addresses appear consistent and professional. Using this script, they can quickly standardise the text in the CSV file, ensuring all client names and addresses are presented in a uniform title case.
