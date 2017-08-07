# Reports-Webapp

The purpose of the webapp is to transfer an authenticated openmrs user session over to the php based reports app (https://github.com/shalewagner/git_iSante) with openmrs. 


## Installing
For general information about openmrs webapps visit - https://wiki.openmrs.org/display/docs/Open+Web+Apps+Module

* Clone or download this repo
* Open the "indicator.json" file in a text editor and set the "url" field parameter to the url of reports website and save. Example
```
{
  "url":"http://myopenmrsreports.com"
}
```
* Select all files and add them to a zip archive. { do not zip the DIRECTORY } - see https://wiki.openmrs.org/display/docs/Open+Web+Apps+Module for details
* Install as an openmrs webapp 
* Set up your reports website as instructed here - https://github.com/IsantePlus/reports-UI
