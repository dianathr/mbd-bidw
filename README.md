# Business Intelligence and Data Warehouse Course

This repository contains all necessary inputs to run the course hands-on labs. 

## Repository contents (by session)

  - Additional articles and documents
  - MySQL Workbench Schemas
  - ETL processes
  - Datasets
  - Tableau files
  - Videos

## Software Installation

  - **Data Warehouse**: MySQL (database) and MySQL Workbench (database modeling and SQL development)
  - **ETL**: Pentaho Data Integration (PDI)
  - **Business Intelligence/Data Visualization**: Tableau Desktop

### Steps

**Install Java**

  - Download Java JDK v8 from: http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html
  - Install and follow the instructions

**Install MySQL**

  - Download the right version of MySQL and MySQL Workbench for your OS 
    - MySQL: http://dev.mysql.com/downloads/mysql/
    - MySQL Workbench: http://dev.mysql.com/downloads/workbench/
  - Install all the programs and follow the instructions:
    - [Windows] During the installation process you will configure the password for root user (choose pentaho)
    - [Mac] A temporal password will be generated. You must start the database from the preferences menu, open MySQL Workbench and the first time you will connect the database you wil have the chance to change the temporal password.

> Note: for Microsoft Windows it is just one installer for MAC, two files.

**Install PDI**

We will use the community version of Pentaho Data Integration (a.k.a PDI). It can be downloaded from this [link](https://sourceforge.net/projects/pentaho/files/Pentaho%208.0/client-tools/).

  - Download the file and unzip.
    - [Mac] Move the data-integration folder into Applications folder
    - [Windows] Move the data-integration folder into C:/ folder
  - Open PDI
    - [Windows] Double-click spoon.bat inside data-integratioon folder
    - [Mac] Open the terminal and execute:
    
```
cd /Applications/data-integration/
./spoon.sh
```    
  - [Optional] Activate data-integration.app as a double-click app using the terminal:
  
``` 
sudo xattr -dr com.apple.quarantine /Applications/data-integration/Data\ Integration.app
```  

  - Install MySQL plugin for PDI:
    - Open PDI
    - Go the tools menu > Marketplace > MySQL Plugin and install
    - Restart PDI

**Install Tableau Desktop**

We can access student licenses due to the Academic Partnership. Tableau has versions for Mac and Windows. Follow these instructions:

  - Download the latest version of Tableau Desktop [here](https://www.tableau.com/academic).
  - Copy Tableau Desktop License from campus.
  - Install the software following the instructions in the screen.
  - Update your license in the application: Help menu -> Manage Product Keys

## FAQ

### Is there a Pentaho Release Product Version Matrix?

Yes! You can find it [here](https://wiki.pentaho.com/display/PEOpen/Pentaho+Release+Product+Version+Matrix+8.x).
