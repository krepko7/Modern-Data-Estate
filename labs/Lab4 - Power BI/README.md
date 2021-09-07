<img style="float: right;" src="../../graphics/solutions-microsoft-logo-small.png">

## Modern Data Estate
# Lab 4 - Create Power BI Report from Data Lake File

In the Azure Portal (portal.azure.com) find your storage accounts.

<img style="float: right;" src="../../graphics/MDL_SelectStorageAccount.png">


Then go into the Access Control (IAM) screen and add a role assignment.

<img style="float: right;" src="../../graphics/MDF_StorageIAM.png">


Add the role "Storage Blob Data Reader" to the Power BI Service ID and click the Save button.

<img style="float: right;" src="../../graphics/MDF_StorageRoleAssignment.png">


In your storage account get the Data Lake Storage endpoint URL from the Settings, Endpoints menu.

<img style="float: right;" src="../../graphics/MDF_StorageEndpoint.png">


Now run Power BI Desktop that was installed as part of your pre-requisite steps.

On first screen in Power BI Desktop click Get Data and then pick the Azure category and Azure Data Lake Storage Gen2

<img style="float: right;" src="../../graphics/MDL_PBI_GetData.png">

Put the URL from your Data Lake storage account and add the container (folder) name.  Green is the Storage Account URL from your endpoints.
Yellow is the container (folder) name and blue is the file name.
The file name is case sensitive.  Example:  https://adlsgen2kirby.dfs.core.windows.net/container1/CarInventoryTextOnly.csv

<img style="float: right;" src="../../graphics/MDL_PBI_URL_In_Color.png">

You will then login to Azure.  Once authenticated you should see a screen like this and you then click the "Transform Data" button.

<img style="float: right;" src="../../graphics/MDL_PBI_Transform.png">

You then will click the Binary link as show below.

<img style="float: right;" src="../../graphics/MDL_PBI_Binary.png">

Now you can start to transform your data. Right click a column and then do things like split a column or transform etc. In this example we are splitting the "Make" column
into two columns.

<img style="float: right;" src="../../graphics/MDL_PBI_TransformETL1.png">

Pick the delimiter and then press OK.  You should now see the one column that transformed into two columns.

<img style="float: right;" src="../../graphics/MDL_PBI_TransformETL2.png">

When finished press the Close & Apply button.

<img style="float: right;" src="../../graphics/MDL_PBI_Apply.png">

Click the upper left Data button in Power BI to see your data.

<img style="float: right;" src="../../graphics/MDL_PBI_Data.png">

Next click the Report button on upper left menu and start creating a new report.  When finished, press the Publish button on top right menu to publish to the Power BI Service (PowerBI.Com)

<img style="float: right;" src="../../graphics/MDL_PBI_Report.png">