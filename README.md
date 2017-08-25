### Welcome to the OFET Database GitHub Repository
Any use of this repository for research purposes must cite (the original paper)[https://doi.org/10.1016/j.cossms.2016.06.002].

# Exploring the Database Online
OFET Database is viewable as a table with interactive filtering and sorting, via this link:
## [Explore the Database](http://nbviewer.jupyter.org/github/Imperssonator/OFET-Database/blob/master/OFET-Table.ipynb)

## Create plots via MatLab GUI

[Download](https://github.com/Imperssonator/OFET-Database/archive/master.zip) the repository to your MatLab active directory.

Run the following command:

OFET_GUI()

Or simply right click on the file "OFET_GUI.m" and select "Run".
A window will pop up from which you can select process constraints and generate plots of mobility against many different independent variables. Minor bugs may be encountered - close the GUI and restart it to reset all fields.

## Exploring the Database as Raw Data
[Download](https://github.com/Imperssonator/OFET-Database/archive/master.zip) the repository to your MatLab active directory.

Run the following command:

load('Functions/OFETDatabase.mat')

The Database should now exist as a structure array called "OFET" in your workspace. Open it in the variable explorer to interact with the raw data.

## View individual papers as Excel sheets
[Download](https://github.com/Imperssonator/OFET-Database/archive/master.zip) the repository to your MatLab active directory.

Open the "Papers" folder, then open the folder for any author, and open the .xlsx file for that paper.

## Add/Edit a paper

#### If you use Git:
* Clone the repository and make your own branch
* Create your own folder in the folder "Papers" and generate your process spreadsheet following the instructions below
* Commit changes to your branch
* Submit a pull request so your changes can be merged back to the master branch

#### If you don't use Git:
* [Download](https://github.com/Imperssonator/OFET-Database/archive/master.zip) the repository to your local machine
* Create your own folder in the folder "Papers" and generate your process spreadsheet following the instructions below
* Email to npersson3@gatech.edu

### How to Add a New Paper
* Create a new folder in the folder "Papers" and name it "\<First Author's Last Name> \<Year of Publication>"
* From the main folder, copy "New Paper Template.xlsx" and add it to your new folder in "Papers"
* Each column in this spreadsheet represents one device
* Each row stores one piece of process information, such as the number average molecular weight of your starting material (Mn)
* Fill in as much information as you can - blank rows are common and perfectly acceptable
* Please use the units specified for each row, which can be found in "Process Variables.xlsx" in the main folder
* For categorical variables such as "solvent", choose from the listed options in "Process Variables.xlsx"
* Spelling and capitalization are important for categorical variables

* Take a look at some of the other papers' spreadsheets as an example


### Disclaimer Statement
This database of organic field effect transistor processing and property data was compiled
by Nils Persson and Michael McBride at the Georgia Institute of Technology. The authors used their best efforts to deliver a
high quality copy of the Database and to verify that the data contained therein have been selected on
the basis of sound scientific judgment. However, the authors make no warranties to that effect, and
shall not be liable for any damage that may result from errors or omissions in the Database.
The Database contains references and links to other web sites because they may have information that
would be of interest to users. No inferences should be drawn on account of other sites being referenced,
or not, from this page.
