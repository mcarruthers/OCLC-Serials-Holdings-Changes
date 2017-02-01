# OCLC-Serials-Holdings-Changes
Process for identifying changes in serials holdings for upload into OCLC Worldshare Knowledge Base.  Uses OpenRefine to compare reports of holdings for two consecutive months to identify additions, changes, and deletions.

Before uploading into OpenRefine, combine the two spreadsheets you will be comparing into one spreadsheet.  
Add two columns to beginning of combined spreadsheet:

1. Row Number - Fill down in sequence to retain original row number of each of the separate spreadsheets.
2. Sheet Date - Fill down the sheet date for each of the separate spreadsheets.

Additional columns (in order): Type, Title, ISSN, eISSN, ISBN10, ISBN13, StartDate, EndDate, PublicationDate, Resource, Subject, URL, Author

OpenRefine will be able to process any spreadsheet upwards of about 1,000,000 rows.  After uploading the spreadsheet, choose the JSON script to run.

Two JSON scripts: one designed to identify additions and changes; the other to identify deletions.

The output can be loaded into OCLC Worldshare Knowledge Base to update holdings.
