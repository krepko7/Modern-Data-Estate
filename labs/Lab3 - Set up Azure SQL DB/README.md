<img style="float: right;" src="../../graphics/solutions-microsoft-logo-small.png">

## Modern Data Estate
# Lab 3 - Set up an Azure SQL Database

>This is the fun part :smile:

In the Azure Portal (portal.azure.com) type "SQL databases" in the search bar at the top of the page then click the SQL Databases option in the search results.

<img style="float: right;" src="../../graphics/SQL_Create.png">

Now press the Create button at the top left.

<img style="float: right;" src="../../graphics/SQL_Create2.png">

Use an existing Resource Group or create a new one.  A Resource Group is simply a logical way to group items in Azure.
Pick No for the SQL elastic pool option.
Before pressing "Next..." click the Configure Database link.

<img style="float: right;" src="../../graphics/sql_create3.png">

In the Configure Database page pick the Save Money option if you already own a SQL Server license.  You can use the sliders at the bottom of
this page to pick the number of vCores and database size. For this lab a 2 vCore with 5 GB should be fine. Click the apply button.

<img style="float: right;" src="../../graphics/SQL_Create4.png">

Pick the Add current client IP address in the networking section.

<img style="float: right;" src="../../graphics/SQL_Create5.png">

Now click the Additional settings section at the top tab and pick "Sample" as the Use existing data option.

<img style="float: right;" src="../../graphics/SQL_Create7.png">

You can now click the Review + create button.

<img style="float: right;" src="../../graphics/SQL_Create6.png">

Review the settings and price details and then press the Create button.

