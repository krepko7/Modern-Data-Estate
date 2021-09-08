<img style="float: right;" src="../../graphics/solutions-microsoft-logo-small.png">

## Modern Data Estate
# Lab 3 - Set up an Azure SQL Database

>This is the fun part :smile:

In the Azure Portal (portal.azure.com) type "SQL databases" in the search bar at the top of the page then click the SQL Databases option in the search results.

<img style="float: right;" src="../../graphics/SQL_Create.png">
&nbsp;

Now press the Create button at the top left.

<img style="float: right;" src="../../graphics/SQL_Create2.png">
&nbsp;

Use an existing Resource Group or create a new one.  A Resource Group is simply a logical way to group items in Azure.
Also, if this is your first SQL DB then you will create a new "Server" in the Database details section.  You can have one "Server" and many
SQL DB's so you only have to create the server once.  This isn't an actual server, it's a way to organize connections, firewalls, networking etc.
Pick No for the SQL elastic pool option.
Before pressing "Next..." click the Configure Database link.

<img style="float: right;" src="../../graphics/sql_create3.png">
&nbsp;

In the Configure Database page pick the Save Money option if you already own a SQL Server license.  You can use the sliders at the bottom of
this page to pick the number of vCores and database size. For this lab a 2 vCore with 5 GB should be fine. Click the apply button.

<img style="float: right;" src="../../graphics/SQL_Create4.png">
&nbsp;

Pick the Add current client IP address in the networking section.

<img style="float: right;" src="../../graphics/SQL_Create5.png">
&nbsp;

Now click the Additional settings section at the top tab and pick "Sample" as the Use existing data option.

<img style="float: right;" src="../../graphics/SQL_Create7.png">
&nbsp;

You can now click the Review + create button.

<img style="float: right;" src="../../graphics/SQL_Create6.png">
&nbsp;

Review the settings and price details and then press the Create button.
Once your database is ready you should see a screen like this. If you don't, click the Bell icon at the top right to see
the status of your database.

<img style="float: right;" src="../../graphics/SQL_Create8.png">
&nbsp;

