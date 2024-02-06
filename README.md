# async-project-template
Support common workflows for collaborative async data analysis.

Folders
* `data_source`: The contents are never modified, and are ignored by github. 
* `data_transformed`: Contents are validated tidy data format, usu csv, and follow naming conventions and best practices.
* `nb_explore`: A folder for free form exploratorations of the data using jupyter and other REPL notebooks
* `nb_final`: A folder for jupyter notebooks. 
* `scripts`: Scripts
* `venv`: contains virtual environment
* The root folder will contain a readme with explanation of steps, as well as: config file, package requirement files (usu. pip and conda). 

Desired and Implemented Features
* [ ] Repeatable, mostly-automated step to apply processing scripts and tranformations. `data_source` --> `data_transformed`
* [ ] Instructions documentation template
* [ ] Rapidly deployable python dashboard using Streamlit, Dash or similar. 
* [ ] Dataset readme and checklist implementation a la Deon
* [ ] Slightly more complex variation of this template that has data validation and deployment options, recalling the Yertle project. 

# Acknowledgements

This repository and template was inspired by Chris Diehl at The Data Guild. 
