---
description: Contains the details about community reports
---

# Community Report

The CHAOSS Community Report is a free service that the CHAOSS community provides to open source communities.

## 🎯 Goals

* Create awareness for the CHAOSS project
* Showcase the CHAOSS metrics and software
* Get more communities interested in CHAOSS metrics and software
* Grow the CHAOSS community

## 😎 Roles

The Community Report processes have the following roles:

* Requester -- Someone asking for a Community Report
* Coordinator -- The CHAOSS contact person coordinating the creation and distribution of Community Reports
* Software Operator -- A person who works with CHAOSS software to generate visualizations

## 📰 Requesting a Community Report

Anyone can fill out a form on the CHAOSS.community website. The form submits to a Linux Foundation system and the form is forwarded to essential CHAOSS community members for processing.

## 💻 Generating a Community Report

When the CHAOSS community receives a request for a report, the following steps will be taken:

1. Someone makes a request
2. Salesforce kicks off the ticket to our emails
3. Vinod, build a new folder for the community request like what I have in the drive now.
4. Vinod, place the SF ticket in the folder
5. Augur and Cauldron generate the graphs for the requested URL and place them into the appropriate folder. Ping Vinod when you're done
6. Vinod, assemble the Community Report by placing the graphs into the .ai document. This will require a bit of sizing but I have the approximate sizes marked in the template. Make sure to maintain ratios. This will also require a little cropping of Augur images at the top to remove some icons that come with the graphs.
7. Vinod, email the report \(in PDF form\) and the SF ticket to Elizabeth \(cc me\)
8. Elizabeth, send the report and SF ticket back to the requestor.
9. If the requestor said it's okay to post it online, I'll get it into the GH folder

### 🍹 Generating visualizations from Cauldron

Detailed steps for generating visualizations from Cauldron (step 5 above), follow these steps:

1. Receive an email from Vinod with information about (1) which repository was requested, (2) what time frame we are analyzing it for, and (3) what Google Drive folder to store visualizations in.
2. Open a new project in Cauldron for the requested repository (information 1) and wait until the data collection is complete (10 minutes to several hours).
3. Set the analysis time frame to the one indicated in Vinod's email (information 2).
4. Make sure the browser is in full-screen size so that the visualizations have a consistent size when downloaded.
5. Use the floppy disk symbol by the visualizations to download them. Navigate to visualizations:
  1. Activity --> Commits --> # Number of commits by hour and weekday (local time of commit author)
  2. CHAOSS --> # Issues created/closed
6. Upload the two visualizations to the Google Drive folder that Vinod created (information 3)
7. Reply to Vinod that the Cauldron visualizations are done
