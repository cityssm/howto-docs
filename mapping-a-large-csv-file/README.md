# Mapping a Large CSV File

Working with a year, or even month sized export of location data
can be extremely difficult, especially when CSV file sized easily exceed 10 GB.

## Create a new folder with the data file

**Never work off the original data.**
Create a new folder with a copy of the data file.
Consider renaming the data file something simple if the file name has a lot of punctuation.

## Prepare the file using KLOGG

[KLOGG](https://klogg.filimonov.dev/) is
which is built to handle extremely large files.

Use filters to remove unnecessary data.
If the file has a month worth of data and only a couple days are needed,
filter out the unnecessary days.

## If the file is fixed width, use Power Query in Excel to make it CSV

Depending on the number of rows, you may need to export multiple time range CSV files.

While Excel is one of the easiest tools to make CSV files,
it also can corrupt data, especially dates, times, and large numbers.
Take care to ensure the important data does not get corrupted.
