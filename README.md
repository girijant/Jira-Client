# Jira-Client
A REST-API based client to export the Jira-Structure into XLS automatically based on JQL (filer-ID) and published into any PowerBI server for Report generation.

# Working Principles:
* JIRA user MUST have to create a Jira-Structure - From multiple jira-projects, export bulk data into a single file format(xls,xlsx,json,xml..etc).
* Run the JiraClient from your local-system which can:
-- Automatically export the jira structure into single xls file based on JQL (filer-ID).
-- Automatically upload the XLS into Sharepoint repo.
* From PowerBI server, configure a scheduler to pull or refresh data periodically from the Sharepoint.
Note: User MUST have to configure their own PowerBI-Template in PowerBI server in order to generate the Reporting Data in terms of Table/Charts/Graphs...etc.

![PowerBi-Jira-Arch](https://user-images.githubusercontent.com/17194046/155484702-8568bcdc-5d95-46db-974e-1a6985f5bd0a.jpg)

# How to Run Jira-Client:
* Download and Unzip the Jira-Client zip.
* From ‘JiraClient/input/jira-client.properties’, update your Credentials, Filter-id and Export-dir/filename details to export the structure.
* User MUST have to close the browser/tabs if any jira-sessions opened in the browser. 
* Run the ‘JiraClient.bat’ to launch the JiraClient and script will wait till the structure-export data is finished.


