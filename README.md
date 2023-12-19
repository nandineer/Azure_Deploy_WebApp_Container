# Azure_Deploy_WebApp_Container



1.	Login to Azure Portal
2.	In the search bar on top of the portal, enter app services.
3.	From the search results, select App Services.
4.	Select + Create.
5.	From the dropdown menu, select + Web App.
6.	On the Create Web App page, in the Basics tab, set the following values:
7.	Resource Group: Select the one available resource group.
8.	Name: Enter cbwebapp001.
9.	Publish: Select Docker Container.
10.	Region: Select the region that matches the location where your resource group was located.
11.	Pricing plan: Select Basic B1.
12.	Click the Next: Docker > button.
13.	On the Docker tab of the Create Web App page, next to Image Source, select Docker Hub.
14.	To get the information needed for the image and tag, open a new browser window or tab and navigate to the Docker Hub website at https://hub.docker.com/r/filebrowser/filebrowser.
15.	Select the Tags tab.
16.	On the righthand side, copy the docker pull/filebrowser/filebrowser:latest command.
17.	Return to the browser window or tab with the Azure portal.
18.	In the Image and tag box, paste the docker pull command that you copied from the Docker website.
19.	Delete the words docker pull from the command, leaving only filebrowser/filebrowser:latest.
20.	Click the Review + create button.
21.	Click the Create button to create the web app
22.	On the webapp overview copy the web app address and enter in browser.



