# **V. Data Sharing & Export**

ResearchArchives allows you to export the content of your project to a GitHub repository. To do this, first we are going to create our repository. If you don’t have a GitHub repository yet and are not familiar with it, you can create an account at https://github.com/. you can read a brief guide on how to create a repository here: https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/create-a-repo (you can stop following the guide once you created a repository.).

Head to the main page of your GitHub repository and select “Settings”.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/git1.png)

Once inside settings, look for “Manage access” on the left pane (1). On this page you can manage who has access to your GitHub repository. In order for RA to be able to push the exported data onto your repository, you will have to give the necessary permissions. To do this, we are going to invite RA as a collaborator. Hit “Invite a collaborator” (2) and enter the username "stashresearch". If you have done everything right, "stashresearch" should appear as a pending invitation under “Manage Access”.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/git2.png)

Now all we have to do is copy the clone git command and paste it inside Sync on RA. Let’s head back to the overview page of your GitHub repository. Just under the “Settings” you can find a big green button labeled “Code” (1). Click on it - make sure that HTTPS is selected (2) - and hit the copy button (3).

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/git3.png)

Now head back to the Sync page in RA and paste the code into the field and hit “Submit”. If everything went well, the data should appear on the main page of your GitHub repository.

![](https://github.com/equarius93/stashtest/blob/main/guide_pictures/sync1.png)