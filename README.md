Gibbs Free Energy README
5/28/2021
Troy Leffel

The goal of this project is to develop an application to predict the reactivity of active materials in a silica glass cane or fiber draw.

Analysis Application holds the original R application which analyzes selected materials from a .xlsx file.  This application is particular to the current format of the .xslx file, and any aditions or edits to the data will result in a complete reformatting of the application.  The desire for a more robust and flexible appliaction lead to the Gibbs Application.

The final goal is the ability to input the materials desired and having the application scrape and process the information automaticallyfrom the NIST website (https://webbok.nist.gov/chemistry/form-ser/).

Rev0 possesses python notebooks containing the rough draft code required to search for the materials on the NIST website and the code required to scrape and sort the website to collect the desired data.
