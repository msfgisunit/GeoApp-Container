# MSF GeoApp-Container


# Workflow
The purpose of the MSF GeoApp-Container is to solve the problems encountered by users of web applications in a local context and without a web server installed on their computer.

**Reminder:** The workflow initially set up for web application users in a local and/or offline context consists in retrieving the GeoApp code files from Github/Sharepoint, and directly executing the "index.html" file to open it in a web browser. Due to browser security patches, this method blocks the application from accessing local files such as user datasets in GeoJSON or CSV/Excel format.

**Old workflow:** 
![N|Solid](https://i.imgur.com/9z28XZl.png)


To get around this problem, an Electron-based application container is made available to GeoApps users. This container contains a folder where to place the GeoApps files, and an executable file that allows the application to be opened via an embedded web server and thus avoid the malfunctions related to the old workflow.

This container being bulky, it is necessary not to duplicate it. When using multiple GeoApps on the same computer, the user must change the GeoApp files in the application container when changing applications.

**New workflow:** 
![N|Solid](https://imgur.com/jAp9iXf.png)

# How-to
- Download MSF GeoApp Container ZIP File on your computer
- Unzip archive
- Places the GeoApp web files in the MSF-GeoApp-Container\resources\app\src\container folder
	>**The index.html file must be at the root of this folder**
- Launch your GeoApp by opening the MSF-GeoApp-Container\MSF-GeoApp-Container.exe file
- If you want to launch another GeoApp, just replace the files in the MSF-GeoApp-Container\resources\app\src\container folder


