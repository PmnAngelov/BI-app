# BI-app - QlikView
Bussines intelligence app made in QlikView, utilisng business analytics, data visualization and data tools and modeling with the purpose of helping the organization make more data-driven decisions. The company's data, presented in the form of visualizations, allows the organization to monitor logistics, sales and productivity.

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/BI-app/blob/main/imgs/Overall.png" />
</p>


The developed BI application strives to improve the bussines performance by using various methods such as different visualizations, data analysis by performing statistical operations on the data sets to gather new insights and create interactive dashboards for management that can be used to monitor KPIs.

In order to load the company's into the QlikView application, a new QlikView document is created in which the data specified by the company will be loaded and the user interface will be developed. The data is loaded after opening the Script Editor, creating a new tab, renaming it with the appropriate name and finally selecting an ODBC (Open Database Connectivity) type database, for a locally located source of data. After loading all five data sources, the data model output is as follows:

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/BI-app-QlikView/blob/main/imgs/FirstDataModel.PNG" width="800" height="400" />
</p>

The tables defined in the QlikView script are called logical tables. QlikView makes associations between tables based on field names and performs the join when a selection is made, for example selecting a field value in a list box. This means that association is almost the same thing as joins. To link identical keys referring to the same data, their name must be changed by the Script Editor. An example of this could be the fact that the product in the Orders table is named ProductKey, while in the Products table it is named Product. To link the two keys, they must be loaded as follows: LOAD ProductKey as Product. The remaining identical pairs are also renamed, and the tables are renamed by adding the corresponding name to the beginning of the script referring to them. After fixing the initial data model, the output is as follows:

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/BI-app/blob/main/imgs/Tables.PNG" width="800" height="400" />
</p>


<p align="center">
<img align="center" src="https://github.com/PmnAngelov/BI-app/blob/main/imgs/MainDashboard.PNG " />
</p>


<p align="center">
<img align="center" src="https://github.com/PmnAngelov/BI-app/blob/main/imgs/Products.PNG" />
</p>

<p align="center">
<img align="center" src="https://github.com/PmnAngelov/BI-app/blob/main/imgs/Resellers.PNG" />
</p>








