# Dataloader-Ant
## Export
### Feature
1. Run data export in sequential batch mode, export multiple objects using one command.
2. Continuously query records by last run time.
3. Output row count and detail log.
4. Delete empty output file.

### Setup
1. Install dataloader and ant.
2. Ant build.xml is in dataloader config folder by default, please specify it in export.bat.
3. Specify object and soql in build.xml, target "all".
4. Specify export folder in build.xml, property "outputFolder".
5. Follow this [help](https://help.salesforce.com/articleView?id=loader_encryption.htm&type=5) for password encryption, specify environmental properties in ${env}.build.properties

### Run
Execute export.bat
