



# Zipper
  
Module to compress and decompress .zip encrypted files .  

*Read this in other languages: [English](Manual_zipper.md), [Português](Manual_zipper.pr.md), [Español](Manual_zipper.es.md)*
  
![banner](imgs/Banner_zipper.png)
## How to install this module
  
To install the module in Rocketbot Studio, it can be done in two ways:
1. Manual: __Download__ the .zip file and unzip it in the modules folder. The folder name must be the same as the module and inside it must have the following files and folders: \__init__.py, package.json, docs, example and libs. If you have the application open, refresh your browser to be able to use the new module.
2. Automatic: When entering Rocketbot Studio on the right margin you will find the **Addons** section, select **Install Mods**, search for the desired module and press install.  


## Description of the commands

### Encrypt Zip
  
Create an encrypted zip
|Parameters|Description|example|
| --- | --- | --- |
|File |Select the file to encrypt|//Users/User/Path/to/file|
|Compression type |Select the compression type|DEFLATED|
|Bits |Select the number of bits|256 bits|
|Password |Enter the password|s3cre7p4ss|
|Ruta donde guardar el zip |Enter the path where to save the zip|//Users/User/path/to/newzip|
|Assign result to a Variable|Variable where True or False will be stored depending on the success of the execution.|Variable|

### Decrypt Zip
  
Get files of encrypted zip
|Parameters|Description|example|
| --- | --- | --- |
|File |Zip file to decrypt|//Users/User/Path/to/file|
|Password |Zip file password|s3cre7p4ss|
|Path where extract zip |Path where extract zip|//Users/User/path/to/folder|
|Assign result to a Variable|Variable where True or False will be stored depending on the success of the execution.|Variable|
