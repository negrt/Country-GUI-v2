# Country-GUI-v2
A C# desktop application that reads data SQL server (express).

# What I learned
* How to use a SQL database to display datasets
* How to Insert data from a JSON file to a SQL database
* How to Remove data from a SQL databse in C#
* OpenFileDialog
* Create a menu bar, with file drop down, exit button, help drop down, about me button
* ListBox data binding with TextBoxes

# More
The application reads country dataset JSON file, store it into ram using a List<country> object, then inserts the data to a 
SQL server database. The application also has the ability to read other country datasets, via OpenFileDialog obj. Before storing
the new country dataset file to the database, the database is cleared, via delete statement, and the data is stored to the
database.
