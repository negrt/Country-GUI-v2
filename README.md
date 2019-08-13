# CountryDataSearchTool-v2
A C# desktop application that reads and inserts data on a SQL server (express).

# What I learned
* How to use a SQL database to display datasets
* How to Insert data from a JSON file to a SQL database
* How to Remove data from a SQL databse in C#
* OpenFileDialog
* Create a menu bar, with file drop down, exit button, help drop down, about me button
* ListBox data binding with TextBoxes

# Images and Description
The application reads country dataset JSON file, stores it into ram using a List of countries, then inserts the data to a SQL server database. The application also has the ability to read other country datasets, via OpenFileDialog obj. Before storing the new country dataset file to the database, the database is cleared, via delete statement, and then the new data is stored in the database.

## Images
#### Start Up
![Image of Country Start Up](https://negrt.github.io/cv/images/CountryStartUp.png)

#### Country Selected
![Image of Country Selected](https://negrt.github.io/cv/images/CountrySelected.png)
