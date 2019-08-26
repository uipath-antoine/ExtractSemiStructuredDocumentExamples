# ExtractSemiStructuredDocumentExamples
Examples for the Extract semi-structured document custom activity

The Extract semi-structured document custom activity can be used to analyze scanned semi-structured documents (invoices and receipts for now) and retrieve various informations (e.g. total paid, currency, tax, items bought, etc.). [The activity is available on UiPath Go!.](https://go.uipath.com/component/extract-semi-structured-document-activity-5abc47)

This repo contains two simple workflows to demonstrate how the Extract semi-structured document works:

### MultipleInvoicesStagingTables
This workflow prompts for a folder containing multiple invoices (format should be png, jpg, bmp, tiff or pdf). All images present in the folder will be sent to UiPath's machine learning model and the results of the analysis will be outputted in an Excel file.

### TestValidationStation
This workflow will prompt for a single invoice file and will present UiPath's ValidationStation to check whether or not the results are correct.
