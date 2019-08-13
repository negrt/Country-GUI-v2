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
![Image of Country Start Up](https://github.com/negrt/cv/blob/master/images/CountryStartUp.PNG?raw=true)

#### Country Selected
![Image of Country Selected](https://github.com/negrt/cv/blob/master/images/CountrySelected.PNG?raw=true)

#### Menu Bar Import Button - Drop Down Open File Button
![Image of Country Open File Dialog](https://github.com/negrt/cv/blob/master/images/CountryOpenFileDialog.PNG?raw=true)

#### New File Opened
![Image of Country New File Opened](https://github.com/negrt/cv/blob/master/images/CountryNewFileOpened.PNG?raw=true)

#### Menu Bar Help Button - Drop down About App Button
![Image of Country About App](https://github.com/negrt/cv/blob/master/images/CountryAboutApp.PNG?raw=true)
