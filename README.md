# CSV/XLSX to Markdown Converter

This Python script converts CSV or XLSX files containing survey responses to a Markdown file with a clean and readable format.

The script lists the first row as questions per respondent & assumes each row from row 2 is a separate respondent.

## Usage

1. Install Python 3.x and required libraries: `pip3 install openpyxl`

2. Replace `your_file.csv` or `your_file.xlsx` in the script with the actual filename of your CSV or XLSX file.

3. Run the script: `python3 convert_to_md.py` ensuring you are in the correct folder

4. The script will generate an output file named `output.md` with the converted contents.
