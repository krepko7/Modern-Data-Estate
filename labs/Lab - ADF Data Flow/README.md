<img style="float: right;" src="../../graphics/solutions-microsoft-logo-small.png">

## Modern Data Estate
# Lab - Azure Data Factory code free data transformations using Data Flows

In the Azure Portal click the search bar in the top and type "Data Factories"
then click on the data factory you created in the earlier lab.

<img style="float: right;" src="../../graphics/DF_FindFactory.png">

Open the Data Factory studio.

<img style="float: right;" src="../../graphics/DF_OpenDF.png">

Look around the Data Factory interface and become familiar with the menu items on the left.

<img style="float: right;" src="../../graphics/DF_Splash.png">

Let's start by setting up a new Linked Service. A linked service is simply a path and set of credentials so Data Factory can find your source of data.

<img style="float: right;" src="../../graphics/DF_NewLinkedService.png">

Pick Azure Data Lake storage Gen2.

<img style="float: right;" src="../../graphics/DF_DataLakeSource.png">

Pick the storage account you created earlier by using your subscription details.

<img style="float: right;" src="../../graphics/DF_Credentials.png">

You should now have a new Linked Service set up.  You will use this for any data set in your data lake
so you won't have to set up another Linked Service for this particular source again.  You will create
other Linked Services for things like a SQL or Oracle database etc.

Next click on the Author menu item and under Data Flows click the three dots (ellipses) and pick New Data Flow.

<img style="float: right;" src="../../graphics/DF_AuthorDataFlow.png">

You can name your Data Flow by filling in the Name property under the Properties window on the top right. 

<img style="float: right;" src="../../graphics/DF_DFName.png">

Click the Add Source box and then give your data set a name.  Name it TaxiData and click the New button.

<img style="float: right;" src="../../graphics/DF_NewSource.png">

Pick Azure Data Lake Storage Gen2 and press Continue.

<img style="float: right;" src="../../graphics/DF_NewDataSet1.png">

Pick CSV and press continue.

<img style="float: right;" src="../../graphics/DF_NewDataSet1.png">

Name your data set and pick the Linked Service you created earlier.  Now browse to the Trip_Data.csv file
in your data lake. Pick the first row as header option.

<img style="float: right;" src="../../graphics/DF_NewDataSet3.png">

Now do the same thing again adding a data source for the Trip_Fare.csv data.

Also, turn on the Data flow debug option.

<img style="float: right;" src="../../graphics/DF_Debug.png">


<img style="float: right;" src="../../graphics/.png">
<img style="float: right;" src="../../graphics/.png">
<img style="float: right;" src="../../graphics/.png">
<img style="float: right;" src="../../graphics/.png">
<img style="float: right;" src="../../graphics/.png">
<img style="float: right;" src="../../graphics/.png">


[Back to main page of tutorial](https://github.com/krepko7/Modern-Data-Estate)