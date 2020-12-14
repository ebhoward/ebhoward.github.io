---
layout: page
title: Quantum IPMP Tools README
permalink: /resources/ipmp
---


### Pre-requisites
You need to be familiar with using QGIS.
You need to have QGIS 3.16 installed.  
<!-- Additionally, install the Qgis2threejs plugin -->

### Installation
1. Download the IPMP.zip file (Right click >Save Link As) from Github. Unzip.

2. Copy *all the files only* in the unzipped scripts folder to the QGIS Processing Scripts folder.  You can check the location of the QGIS Scripts folder as follows:

    QGIS >Setings >Options >Processing >Scripts

    If the folder does not exist, create it by typing in your desired folder.

3. Create and save a new QGIS Project.  Copy the unzipped *qsettings folder and all its files* into you newly created project folder.  You can check the location of the project folder as follows:
    QGIS >Project >Properties >Variables >Project >project_folder

3. Set the project CRS:
    QGIS >Project >Properties >CRS>

4. Optional: click on the + button at the bottom right and add a new variable project_font_size.  Type in your desired size - for example, 8, or 14 et cetera.  

5. Copy all the files in the unzipped samples folder into your newly created QGIS project folder.  Drag and drop the files into QGIS.

### Using the QuantumIPMPTools
1. The Quantum IPMP Tools are available from:
    QGIS > Processing >Toolbox >Scripts
    
    