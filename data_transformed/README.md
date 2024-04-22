
## Folder: data_transformed
This folder contains processed and in-flight data. These data are usually created by preprocessing scripts that perform join, clean, and other munging operations. 

Recommended practices:
* Do not upload data files to github. Use `.gitignore` accordingly. 
* When possible, transformed data should be in "tidy" format. 
* Consider [Great Expectations](https://github.com/great-expectations/great_expectations) or implementing a few unittests to ensure data integrity. 


Tidy datasets format
* Each variable is a column, each observation is a row, and each type of observational unit is a table.
* Flat file format (like CSV), or other formats that can be directly imported using python pandas
* see [source by Hadley Wickham](https://vita.had.co.nz/papers/tidy-data.html) 

--- 

This folder is part of a template. 
https://github.com/gofenris/async-project-template/
