# MPESA Statement PDF to Excel Converter

## Overview

This Jupyter Notebook allows users to convert encrypted MPESA statement PDFs to Excel format using the provided password from Safaricom. It is a useful tool for individuals who want to analyze and understand their MPESA statements in spreadsheet applications like Excel.

## Prerequisites

Before using this script, ensure that you have the following:

- Jupyter Notebook installed on your system.
- Required Python libraries installed. You can install them by running the following command in a Jupyter cell:

  ```python
  !pip install camelot-py[cv] pandas openpyxl
## Usage
### 1. Clone the repository:
Navigate to a folder within your system where the script will be stored and used, then clone this repository.

  ```python
git clone https://github.com/mithiga/PDF-to-Excel.git
cd PDF-to-Excel
```
### 2. Open the Jupyter Notebook:
 ```python
jupyter notebook MPESA-Statement-PDF-to-Excel.ipynb
```
### 3. Update script variables:
- Open the Jupyter Notebook and locate the first cell within the script.
- Modify the `file_path`, `output_path`, and `password` variables as needed.
- Provide the password received from Safaricom.
- Ensure the input file name matches the actual pdf statement you have
- Execute each of the two cells in the notebook.
- The notebook will convert the PDF to Excel format using the camelot library and save it using openpyxl and save the output Excel on the same folder.

## Notes
- Ensure that you have the necessary permissions to access and decrypt the MPESA statement PDF.
- Make sure to keep your Safaricom password secure and do not share it with others.
- The converted Excel file will be saved in the same directory as the notebook.

## Disclaimer
This notebook is provided as-is without any warranty. Use it at your own risk and make sure to comply with Safaricom's terms and conditions regarding the usage of MPESA statements.
This README assumes that your Jupyter Notebook is named `MPESA-Statement-PDF-to-Excel.ipynb`. Adjust the file names, URLs, and other details as needed.

## Contribution
Feel free to contribute to the improvement of this notebook by opening issues or pull requests.

Happy analyzing your MPESA statements!
