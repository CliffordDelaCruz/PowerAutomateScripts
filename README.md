# PowerAutomateScripts
Power Automate scripts saved as a text file
***
Add PowerAutomate script saved in text file
### 06/30/2023 - Upload "Invoice_Reprocess_V2"
_**Purpose**_:  
This automation script is created for the purpose of re-processing data extraction of PDF invoices that failed to upload.
The steps are:  
1. Take the CSV list of failed invoices that were not successfully uploaded
2. Create a new CSV file and save to a specific folder location for processing
3. Read through all the invoice to pick up the invoice PDF
4. Create a BAT file which will execute to copy the PDF files to specific folder location for processing
