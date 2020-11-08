**Disclaimer**

The first part of this Guide is written in a way that you can set up your own test project in STASH by following it step-by-step. In order to get the demonstration material which we have used in the guide, please visit: [https://github.com/equarius93/stashtest/blob/main/video demonstration covid.csv](this link). Please save this file on your computer and also add it to a Google Drive folder which you are going to be using as a data source. This file contains some COVID-related data about Afghanistan from 2019. Please make sure to transform this file into a Google Sheets document in your Google Drive folder.

**I. Profile and Project Registration****I.1 Profile Registration and Login**	In order to use the STASH website, you are going to need a registered account. On the main page of the website, click on „Register”.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/reg1.png)

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/reg3.png)

After filling out the required information, hit submit and you are going to receive a confirmation email to the email you’ve specified. Now you can log in.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/Login.png)

**I.2 Project Registration**	For each of your projects you are going to need a separate project registration. In order to register a project, head to the front page of the site and hit ,,create project”.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/proj1.png)

On the following page you will have to give a name and a description for the project. you can fashion the description whatever way you would like to. We advise that you try to summarize your project. you can make the project either public or private. Public projects’ data will be readable by everyone, private project data will only be available to collaborators.

Please note that the name, description and the type (public or private) of the project cannot be changed later in the current version of STASH.

Hit “Create” when you are done. On the next screen you are going to have to give your account’s password to ensure the safety of your data.

We take the security of your data extremely seriously and have multiple features built in to STASH that can guarantee that only you and your specified collaborators (feature upcoming) have access to the data.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/proj2.png)

After you have confirmed your account password, you are going to be greeted by a data encryption page. Please make sure that you save the recovery key to a private and secure place. You can check your recovery key anytime under project→settings→security.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/security.png)

You are going to need this in case you forget or lose the password of your Account. Save your recovery key and hit “submit” to continue.

**I.2.2 Data Source for the Project**

Now we have our project created, time to fill it with content. First we are going to have to add a data source, from which Stash is going to pull the data.

After the data encryption page you are going to be greeted by the overview page of your project. To add a data source, head over to “Settings” and select “Data Sources” on the left pane. As of now this should be empty, select ,,Add a Data Source”. Please note that the name of the data source needs to be unique within a project.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup1.png)

As of now, there are two kinds of data sources in STASH: Google Sheets (this includes the google sheets in which Google Forms collect data) and manual upload of .csv files. FormR is also going to be supported in the future.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup2.png)

**I.2.2.1 Google Sheets/Forms**

This section tells you how to link a Google Sheet as a data source to STASH. First of all you are going to need a Google Sheet file. For a demonstration material please follow [this link](https://github.com/equarius93/stashtest/blob/main/video demonstration covid.csv).

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup1.png)

Head inside your project, and then (1) Settings→ (2) Data Sources. Hit (3) Add a Data Source.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup2.png)

On the following page you are going to see several methods for adding data sources. hit “link your google account”.

A Google login page will pop up. You will have to grant STASH certain permissions, which you can read on the page. Stash will only ask access to the specific file that you have selected, so it won’t have access to any other files or folders on your Google Drive. Make sure to hit “Allow” before you close the window. Please note that currently only one Google account can be linked to a STASH account.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup3.png)

Now that you’ve given all the necessary permissions to RA you should refresh the data source page. As you can see, a “Link new file” option appeared under “Google Forms / Sheets”. Click on that to proceed.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup4.png)

A window is going to pop up where you can select the file which contains your database. Please note that it has to be a Google Sheets file. you can use the search field to look for your file.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup5.png)

On the following screen you can see the headers of your data. On this page you have the option to mark columns as personal data, omit columns and select an observation key.

You have to specify an Observation Key column. should be a field which is unique to each row in the dataset. This serves as a row identifier for Stash to better be able to determine what was changed in the dataset between different versions of the dataset. This allows us to mark the reordering of the observations without flagging a change in the data. If you don’t use any observation key then the number of the rows are going to be used for this purpose. In this case if you reorder the rows in the source dataset, Stash will flag a change in the data change history.

All columns marked as containing Personal Data will be encrypted. The decryption key for this data is linked with your user password so that no one can see these data fields without permission.This has been added as an extra security measure to ensure the safety of any personal or sensitive data. Note that not even the RA team can access data encrypted this way. This means that if you forget your password, the data cannot be recovered by the RA team.

Make sure to save the recovery key to your project securely! You can check your recovery key later on inside your project→settings→Security. If you have to reset or change your password for some reason, the new password will NOT unlock the encrypted data, because the decryption key is linked with the password with which you encrypted the data. The only way to recover the encrypted data is via supplying the password you used then, or by supplying the recovery key that is presented to you at the creation of the project. That is why it is very important to save the recovery key for your projects securely.

Once you have done the data setup there is no way to change the options.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasource3.png)

Whenever you add a new data source, you should make sure that it has been added by going over to the “Data Sources” inside “Settings” in your project.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/datasetup6.png)

As you can see, there are several things that you can do to manage your sources here. Also if you head over to the “Data” page inside your project, you should see the complete dataset. For a more detailed description about the data page and data sources, please guide number 2 called "User interface".

**I.2.2.3 CSV File**

If you would prefer to upload your dataset from a file manually, you have to make sure that it is saved in a .csv file format. Head inside your project, and then Settings/Data Sources/Add a Data Source. Under CSV Upload, hit “Browse your files” or just drag and drop the file there.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/CSV1.png)