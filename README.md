##GettingandCleaningData
======================
###Introduction
The R Script found in run_analysis.R should be run from your working directory.

The working directory must contain the folder UCI HAR Dataset with the file structure intact.

### Data transormation
The script takes the the data regarding the observed activities and creates one table.

Decriptive names replace the numeric activity identifiers.

The train data and the test data are combined.

Columns of unneeded data are removed.

Desciptive names are added for variables.

The data is grouped by subject and activity and the mean of the observtions is returned

### Output
The script creates a file "meandata.txt" in the working directory containing the summarized data

