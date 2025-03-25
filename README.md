# Leica Trades Python
A reverse-engineering of the Leica iCON Trades software in python.

# Testing
I have tested this software using the Leica iCON iCS50 machine.

![2025-03-25 224 bar scan](https://github.com/user-attachments/assets/a1eec491-7904-46fe-9119-5639ad145eb6)

- Leica Trades app stores all information in the iCON trades folder on the android tablet.
- Within the Projects folder, there is a folder for each project in the format of <project name>.irmprj
- Within each project folder, there are folders for each job. These are in the format <job name>.irm
- Within each job folder, there are the following items
  -  "Import" folder
  -  "LiveView" folder
  -  "Panorama" folder
      - Contains panoramas from the project (if any were taken) in JPEG format.
  -  JobName.inf
  -  JobName.irm
  -  JobName.thumbnail
      - This is actually just a PNG image. You can rename it to ".png" to view it.
