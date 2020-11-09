# Data Source Guide

This guide shows you how to add and manage data sources on Stash.

**Disclaimer**

In order to do this part of the guide you are going to need a Google Sheets file on your Google account and a .csv file. In order to get the demonstration material which we have used in the guide, please visit the following link: https://docs.google.com/spreadsheets/d/1GHP_QrN9rmHRzhfyhzQtHWPAC32XK9PBtBeMGFJQ9Jw/edit?usp=sharing . You can upload this to your Google Drive account. In order to create a Google sheet from this, locate the file, right click on it, go into ,,open with" and select "Google Sheets".

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/sheets.png)

## I.1 Manage Data Sources

To manage your data sources, head inside your project and go to (1) *Settings* and select (2) *data sources* on the left pane.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasource5.png)

If you can see your data sources here if you have already added one. You can see the (3) *name* of the data sources, the (4) *source type* (either Google or csv). You also have a direct link to the data source here if you have added the data source from Google. You can also download the data table if you click on (5) *raw data*, but the personal info is going to be encrypted. Under (6) *Sync* you can check the status of your data sync. You can also (7) *delete* the data sources you don't need anymore.

If you don't have any data sources yet or if you would like to add a new one, hit (8) *add a new data source*.

### I.1.2 Add new data sources

To add a new data source, head inside your project and go to (1) *Settings* and select (2) *data sources* on the left pane.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup1.png)

Select (3) *add a new data source*. On the following page you can add either a Google Sheets file or you can manually upload a .csv file.

#### I.1.2.1 Add a data source from Google

In order to add a data source from Google, first you are going to need a Google account. If you are not familiar with Google, here is a short guide with which you can create an account: https://support.google.com/drive/answer/2424384?co=GENIE.Platform%3DDesktop&hl=en .  To do this part of the guide you are also going to need a Google Sheets file on your Google Drive.

In order to get the demonstration material which we have used in the guide, please visit the following link: https://docs.google.com/spreadsheets/d/1GHP_QrN9rmHRzhfyhzQtHWPAC32XK9PBtBeMGFJQ9Jw/edit?usp=sharing . You can upload this to your Google Drive account. In order to create a Google sheet from this, locate the file, right click on it, go into ,,open with" and select "Google Sheets".

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/sheets.png)

After following the path: project Settings/data sources/add a new data source; you can select your Google account.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup2.png)

A Google login page will pop up. You will have to grant STASH certain permissions, which you can read on the page. Stash will only ask access to the specific file that you have selected, so it won’t have access to any other files or folders on your Google Drive. Make sure to hit “Allow” before you close the window. Please note that currently only one Google account can be linked to a STASH account.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup3.png)

Now that you’ve given all the necessary permissions to STASH you should refresh the data source page. As you can see, a “Link new file” option appeared under “Google Forms / Sheets”. Click on that to proceed.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup4.png)

A window is going to pop up where you can use the (1) search field to look for your file or select (2) the file which contains your database. Please note that it has to be a Google Sheets file.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasource6.png)

On the following screen you can see the headers of your data. On this page you have the option to mark columns as personal data, omit columns and select an observation key. For further information please check ***I.1.2.3 Data Setup*** part of this guide.

#### I.1.2.3 Data Setup