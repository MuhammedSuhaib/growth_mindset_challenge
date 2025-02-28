# Data Sweeper

## Overview
Data Sweeper is a simple web app built with Streamlit that allows users to upload, clean, edit, and convert CSV and Excel files with ease.

## Features
- Upload CSV and Excel files
- Preview and edit uploaded files
- Remove duplicate rows
- Fill missing numeric values with column means
- Select specific columns for processing
- Visualize numerical data with bar charts
- Convert files between CSV and Excel formats
- Download the processed files

## Installation
1. Clone this repository:
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Open the app in a browser after running the Streamlit command.
2. Upload CSV or Excel files using the file uploader.
3. Edit the dataset directly in the interactive table.
4. Apply data cleaning options if needed.
5. Select columns for further processing.
6. Visualize data and download the cleaned file in the preferred format.

## Dependencies
- Python
- Streamlit
- Pandas
- OpenPyXL (for Excel file handling)

## License
This project is licensed under the MIT License.

