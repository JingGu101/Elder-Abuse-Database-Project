# Description of Project Files
This section is going to describe the different folders and files within this project:

files: example files used to test functionalities

static: the folder that holds the css files used to stylize the pages

templates: the folder that holds the html files

uploads: the uploads folder is used to store the attachments that are associated with the cases

app.py: the main file that has the main logic and routes

docToSql.py: file used to handle logic from turning microsoft word form to sql database

worddocparser.py: file that was developed by last year's team to parse the Microsoft word form

sqlScript.txt: file that includes the SQL to create the database

requirements.txt: list of dependencies and their versions



# Elder-Abuse-Database-Project

How to run project:

First make sure you have python installed. Then you can download the dependencies that are located in the requirements.txt file. You can do so with the following command: `pip install -r ./requirements.txt`


Now run `flask --app app --debug run` 
