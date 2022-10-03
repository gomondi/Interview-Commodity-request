# PowerBI-integration
Data>powerbi/tableu integration
Add Odata Feed
Select field type>case
App type:application
Application: (name of the application)
Case type: request
Copy Odata feed link

# Link powerBI with Commcare
Open powerBI>get data>Odata feed
Paste link and hot OK
Log in using your credentials on basic tab

# Graph calculation
Please see the text files for dax calculations

# Publish to PowerBI service
Click on publish and log in powerBI service

# How to make service report sharable
Step 1. File> Embed reports>Publish to web
Step 2. Copy link 1

# Auto request data from commcare
Step1. Click on schedule refresh in the dataset settings

Step 2. Configure Data source credentials
a.	Edit credentials
b.	Authentication method >basic
c.	Sign with commcare user and password
d.	Privacy level setting for this data >public
e.	**DO NOT skip test connection**

Step 3. Schedule refresh >ON
a.	Time >Add another time
b.	Set desired refresh time
c.	Repeat process to get refresh every hour
d.	Apply Changes	
