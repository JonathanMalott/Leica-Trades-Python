# Leica Trades Python
A reverse-engineering of the Leica iCON Trades software in python.

# Testing
I have tested this software using the Leica iCON iCS50 machine.


- Leica Trades app stores all information in the iCON trades folder on the android tablet.
- Within the Projects folder, there is a folder for each project in the format of <project name>.irmprj
- Within each project folder, there are folders for each job. These are in the format <job name>.irm
- Within each job folder, there are the following items
-  "Import" folder
-  "LiveView" folder
-  "Panrama" folder
-  <Job Name>.inf
-  <Job name>.irm
-  <Job Name>.thumbnail
