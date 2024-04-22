
## Folder: data_source
This folder contains source data files utilized in the project. 

Recommended practices:
* Scripts and notebooks should never modify data files located in this folder.
* Do not upload data files to github. Use `.gitignore` accordingly. 
* Upload synthetic or sanitized sample data here instead. 
* Consider storing original source data on an access-controlled service like s3, and fetching it programmatically. 

If data is joined / munged /processed, write processed data files to the folder `data_transformed`. 

--- 

This folder is part of a template. 
https://github.com/gofenris/async-project-template/
