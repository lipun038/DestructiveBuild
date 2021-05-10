# Salesforce SFDX Destructive Build

### Step 1 : Download and install SFDX CLI from the below URL :
  - https://developer.salesforce.com/tools/sfdxcli

### Step 2: Make sure to include the SFDX instalation folder path into your environment variable
  - %PATH% = C:\Program Files\Salesforce CLI\bin

### Step 3 : Clone/Download this repo to your local machine.

### Step 4 : Open the config.txt file and make sure for the foirst line target org equals nothing.
  - targetOrg=

### Step 5 : Levaing target org blank allows you to authenticate and auto populate the target org alias after the equal to symbol.

### Step 6 : Update the .\metadata\destructive\destructiveChanges.xml file with list of components you wanted to remove/delete.

### Step 7 : Run the sfdxcmd.bat file and follow the instruction.

### Step 8 : Make sure to remove the dependency with a;ll the components you wanted to delete, before running the destructive build.

### Step 9 : If everything went well, you are done :)  
