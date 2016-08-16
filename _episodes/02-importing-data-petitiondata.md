---
title: "Importing data into OpenRefine"
teaching: 10
exercises: 5
questions:
- "How do I get data into OpenRefine?"
objectives:
- "Successfully import data into OpenRefine"
keypoints:
- "Use the 'Create Project' option to import data"
- "You can control how data imports using options on the import screen"
---

## Importing data

### Exercise 1: Create your first Open Refine project (using provided data)
There are several options for getting your data set into OpenRefine. You can upload or import files in a variety of formats including:

* TSV (tab-separated values)
* CSV (comma-separated values)
* Excel
* JSON (javascript object notation)
* XML
* Google Spreadsheet

To import the data for the exercises below, run OpenRefine and:

* Click 'Create Project'
* Choose 'Get Data from this Computer'
* Click 'Choose Files'
* Locate the file called 'petitions-archive-list.xlsx' which you previously downloaded
* Click 'Next'

The next screen gives you some options to ensure that the data gets imported into OpenRefine correctly. The options vary depending on the type of data you are importing.

In this case you need to:

* Make sure 'Store blank rows' is checked
* Make sure 'Store blank cells as nulls'
* Ensure the first row is used to create the column headings

Note that you can specify the number of rows to load, and gives you the ability to discard any number of initial rows.

Once you are happy click 'Create Project >>'

This will create the project and open it for you. Projects are saved as you work on them, there is no need to save copies as you go along.

To open an existing project in OpenRefine you can click 'Open Project' from the main OpenRefine screen (in the lefthand menu). When you click this, you will see a list of the existing projects and can click on a project's name to open it.

### Going Further
* Look at the other options on the Import screen - try changing some of these options and see how that changes the Preview and how the data appears after import.
* Do you have access to JSON or XML data? If so the first stage of the import process will prompt you to select a 'record path' - that is the parts of the file that will form the data rows in the OpenRefine project.
* Data citation (minor changes in delimiters were done to facilitate exercises):  Digital Archive of Massachusetts Anti-Slavery and Anti-Segregation Petitions, Massachusetts Archives, Boston MA, 2016, "Senate Unpassed Legislation 1874, S 26 adopted resolutions, SC1/series 231, Petition of Thomas B. Reed", http://dx.doi.org/10.7910/DVN/YUS6ZD, Harvard Dataverse, V2
