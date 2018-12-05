# SFDX  App
Starter Geolocation Application in Salesforce that locates and drops pins onto map of locations according to Longitude and Latitude. 
<br>

![alt text](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/modules/sfdx_app_dev/sfdx_app_dev_create_visuals/images/f7f2e41264a11b943416046f601e6796_acct_map_pins.png)

## Dev, Build and Test

 force:alias        manage username aliases
 <br>
 force:apex         work with Apex code
 <br>
 force:auth         authorize an org for use with the Salesforce CLI
 <br>
 force:config       configure the Salesforce CLI
 <br>
 force:data         manipulate records in your org
 <br>
 force:doc          display help for force commands
 <br>
 force:lightning    create and test Lightning component bundles
 <br>
 force:limits       view your org’s limits
 <br>
 force:mdapi        retrieve and deploy metadata using Metadata API
 <br>
 force:org          manage your orgs
 <br>
 force:package      develop and install packages
 <br>
 force:package1     develop first-generation managed and unmanaged packages
 <br>
 force:project      set up a Salesforce DX project
 <br>
 force:schema       view standard and custom objects
 <br>
 force:source       sync your project with your orgs
 <br>
 force:user         perform user-related admin tasks
 <br>
 force:visualforce  create and edit Visualforce files

## Resources
https://trailhead.salesforce.com/content/learn/modules/sfdx_app_dev?trail_id=sfdx_get_startedsf

## Description of Files and Directories

/config/project-scratch-def.json 
Location for starting scratch org :
sfdx force:org:create -f config/project-scratch-def.json -a TestOrg1

/data/Account.json
Test records with latitude and longitude EX: Latitude: 37.785143, Longitude: -122.403405

/force-app/main/default
/aura 
Location of lightning components
/classes
Location of Apex Classes controller

## Issues
2018.12.05 updated ReadMe 

