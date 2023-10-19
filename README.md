# Bank_ETL

<h2>Project Senario</h2>

<p>
create a code that can be used to compile the list of the top 10 largest banks in the world ranked by market capitalization in billion USD. Further, the data needs to be transformed and stored in GBP, EUR and INR as well, in accordance with the exchange rate information that has been made available to you as a CSV file. The processed information table is to be saved locally in a CSV format and as a database table.

Your job is to create an automated system to generate this information so that the same can be executed in every financial quarter to prepare the report.
</p>

<h2>Project Tasks</h2>

<ls>
<li>Task 1:</li>
<ul>Write a function log_progress() to log the progress of the code at different stages in a file code_log.txt. Use the list of log points provided to create log entries as every stage of the code.</ul>

<li>Task 2:</li>
<ul>Extract the tabular information from the given URL under the heading 'By market capitalization' and save it to a dataframe.</ul>
<ul>a. Inspect the webpage and identify the position and pattern of the tabular information in the HTML code</ul>
<ul>b. Write the code for a function extract() to perform the required data extraction.</ul
<ul>c. Execute a function call to extract() to verify the output.</ul>

<li>Task 3:</li>
<ul>Transform the dataframe by adding columns for Market Capitalization in GBP, EUR and INR, rounded to 2 decimal places, based on the exchange rate information shared as a CSV file.</ul>
<ul>a. Write the code for a function transform() to perform the said task.</ul
<ul>b. Execute a function call to transform() and verify the output.</ul

<li>Task 4:</li>
<ul>Load the transformed dataframe to an output CSV file. Write a function load_to_csv(), execute a function call and verify the output.</ul>

<li>Task 5:</li>
<ul>Load the transformed dataframe to an SQL database server as a table. Write a function load_to_db(), execute a function call and verify the output.</ul>

<li>Task 6:</li>
<ul>Run queries on the database table. Write a function load_to_db(), execute a given set of queries and verify the output.</ul>

<li>Task 7:</li>
<ul>Verify that the log entries have been completed at all stages by checking the contents of the file code_log.txt.</ul>


</ls>
