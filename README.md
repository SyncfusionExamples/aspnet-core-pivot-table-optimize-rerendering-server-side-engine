# how to optimize the re-rendering of a pivot table when using a server-side engine

A quick start project that helps you on how to optimize the re-rendering of a pivot table when using a server-side engine.

## How to run this application?

The following steps demonstrate how to run the application,

* Open the [PivotController](./PivotController/) application in Visual Studio.
* Dependent packages will be downloaded automatically from the nuget.org site.
* Run the application once the packages are downloaded.
* Once the application is hosted in the localhost, copy its URL.
* Then open [PivotTable](./PivotTable/) application in Visual Studio and navigate to the **PivotTable -> Views.cshtml** paste the copied URL **dataSourceSettings->url** property.
* Now run the application, the pivot table will populate in the browser.