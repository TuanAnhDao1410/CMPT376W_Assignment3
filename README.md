# LogLens

LogLens tells you what's happening in your logs. LogLens reads a CSV log file and counts its records. You can count all records
or choose one log level, such as `ERROR`. The file stays on your computer, your data is always 100% secure.

## Requirement

- Python 3.8 or newer.
- A CSV file containing three column names: 'date', 'severity', and details'.

For first run, use command [command].
If you need to download the project, follow. the install guide in (docs/INSTALL.md).

## Get started

1. On the project's GitHub page, click **Code**, then **Download ZIP**.
2. Extract the ZIP file.
3. Open a terminal in the folder that contains `loglens.py`.

If you need to download the project, follow. the install guide in (docs/INSTALL.md).

## Using the program

In the terminal you opened during setup, run the following command:

`loglens --input mylog.csv --severity error`

The software scans your log, fixes mistakes, and shows you what went wrong. You will see a number once it is finished. You can also run it on real production files without worrying about any side effects.

## Questions

If a command fails, check the (docs/INSTALL.md). If you still need help, open a GitHub issue and include:

- The command you ran.
- The error message you saw.

Remember to remove private details before posting. If you need to share an example, only send the relevant rows.
