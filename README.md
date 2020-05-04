Module8_Challenge - Allen Shih

Background
While ETL can absolutely be used for a one-time transfer of data, it becomes really powerful when it can be automated as a repeated, ongoing process. Since this process will be running without supervision, it won’t be necessary to perform the exploratory data analysis steps. However, if new incoming data contains errors, the ETL process may halt or produce corrupted data. Adding try-except blocks will make the automated ETL script more robust to errors.

Objectives
The goals of this challenge are for you to:

Create an automated ETL pipeline.
Extract data from multiple sources.
Clean and transform the data automatically using Pandas and regular expressions.
Load new data into PostgreSQL.
Instructions
For this task, assume that the updated data will stay in the same formats: Wikipedia data in JSON format and Kaggle metadata and rating data in CSV formats. Follow these steps:

Create a function that takes in three arguments:
Wikipedia data
Kaggle metadata
MovieLens rating data (from Kaggle)
Use the code from your Jupyter Notebook so that the function performs all of the transformation steps. Remove any exploratory data analysis and redundant code.
Add the load steps from the Jupyter Notebook to the function. You’ll need to remove the existing data from SQL, but keep the empty tables.
Check that the function works correctly on the current Wikipedia and Kaggle data.
Document any assumptions that are being made. Use try-except blocks to account for unforeseen problems that may arise with new data.


Solving Steps:
1. The updated data will be in the same formats.
2. We created a system to transform for best answer.
3. We dropped rows with bad data when two movies fot merged.
4. We dropped columns with one number.
5. New file will have new section of "New files to updload"