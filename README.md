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

The tables defined in the QlikView script are called logical tables. QlikView makes associations between tables based on field names and performs the join when a selection is made, for example selecting a field value in a list box. This means that association is almost the same thing as joins. To link identical keys referring to the same data, their name must be changed by the Script Editor. An example of this could be the fact that the product in the Orders table is named `ProductKey`, while in the Products table it is named `Product`. To link the two keys, they must be loaded as follows: ```LOAD ProductKey as Product```. The remaining identical pairs are also renamed, and the tables are renamed by adding the corresponding name to the beginning of the script referring to them. After fixing the initial data model, the output is as follows:

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


The company has a total of 60855 orders placed since its beginning and has generated $79,980,114.38 in revenue. They sold a total of 214378 items, with the largest order placed for 44 items and the smallest for 1 articul. The top five most active partners are also visible, being: Friendly Bike Shop, Sports Product Store, Ultimate Bake Shop, Metropolitan Equipment and Fitness Toy Store. Also pictured are the top five best selling items. Finally, it is also clearly visible that the company's revenues are increasing with each passing year, meaning that the company has taken the right direction of development. On the Resellers dashboard shown above, it can be seen that the top five most active partners are: Friendly Bike Shop, Sports Product Store, Ultimate Bake Shop, Metropolitan Equipment and Fitness Toy Store. The most sales are dony by Warehouse businesses, followed by Specialty Bike Shop businesses and finally, Value Added Reseller businesses. The block graph shows that the United States of America (US) is the largest market for the company, followed by Canada (CA), Germany (DE), Great Britain (GB), France (FR) and finally Australia (AU).









