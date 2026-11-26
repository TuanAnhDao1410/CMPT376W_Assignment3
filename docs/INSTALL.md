# How to install LogLens and use it

Follow these steps to set up LogLens and run it with the sample CSV file. LogLens reads the file on your computer and leaves it unchanged.

## Things you need

* Python 3.8 or newer, plus pip.
* A network connection so LogLens can upload your files for checking.
* A file containing logs from your computer or a work system.

## Getting the program

1. Open the project's main page on GitHub.
2. Click **Code**, then **Download ZIP**.
3. Extract the ZIP file.
4. Find the folder that contains `loglens.py`. Open a terminal in that folder.

Run this command:

pip install loglens

Then move on to the next step.


## Running a check

Start with the sample file. From the folder that contains `loglens.py`, run:

python loglens.py data/sample_logs.csv

For your own files, type `python loglens.py --file /Users/alex/Desktop/system-log.csv --level error`. This will print results when the analysis is over. You can find the example data in data/sample_logs.csv in the project's 'data' folder

## Problems and fixes

If you see a "file not found" error, reinstall Python and try again. If the software complains about the CSV, there might be something wrong with your system. If you still need help, open a GitHub issue. Include the command you ran and the error message you saw. Remove sensitive details before posting. If you need to show an example, use only relative rows with made up data.
