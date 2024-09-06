<<<<<<< HEAD
# Phase 1 Project Templates and Examples

This repo contains templates and examples to help you get started with your Phase 1 Project. Each of these is in a separate branch as explained below.

- The **template-mvp** branch is the template you should use to for your Phase 1 Project. MVP stands for Minimum Viable Product, but this isn't meant in a negative way - if your project uses this template, it will be functional and accessible.

- The **example-mvp** branch is an example project using the MVP template.

Once you've completed your project using the MVP template, you can improve it using the Above and Beyond (AAB) template if you have time:

- The **template-aab** branch is the AAB template to use to keep improving your project.

- The **example-aab** branch is an example project using the AAB template.
=======
# Phase 1 Project Template - Above and Beyond (AAB)

This version of the repository template builds upon the MVP version. It incorporates best practices for project organization and code modularization.

## Code Modularization

The main difference between this AAB version and the MVP version is modularization of code. Code for data preparation and visualization is placed in separate .py files that are then imported into the Jupyter Notebook. This allows your Jupyter Notebook to be much easier for a third party to run and interpret, without having to weed through all the messy details. Modularizing code is a key programming skill that makes it easy to maintain, upgrade, and deploy your projects. Doing this will not only make it easier for you to work on your projects, but it will also show potential employers that you value usability in your code.

Note that you must include the `__init__.py` files in the root directory and subfolders containing any code that you wish to import.

## Repository Contents

Below is a list of the contents of this repository.

- `README.md`: The README for this repo branch explaining it's contents - you're reading it now
- `TEMPLATE_README.md`: An example of a project README that provides a brief overview of your whole project
- `dsc-phase1-project-template.ipynb`: A starter Jupyter Notebook with headings, code examples and guiding questions
- `DS_Project_Presentation_Template.pdf`: A starter slide deck presenting your project - here is an [editable version](https://docs.google.com/presentation/d/1PaiH1bleXnhiPjTPsAXQSiAK0nkaRlseQIr_Yb-0mz0/copy)
- `__init__.py`: Python helper file that tells Python that there are packages in the repository that can be imported
- `zippedData` folder: A folder for the data you reference with your code
- `images` folder: A folder for the images you reference in your files
- `code` folder: A folder for the python scripts that your Jupyter Notebook imports
  - `__init__.py`: Python helper file that tells Python that there are packages in this folder that can be imported
  - `data_cleaning.py`: Code to prepare data for analysis
  - `visualizations.py`: Code to produce visualizations
  - `eda_notebook.ipynb`: Notebook with any messy EDA so the main notebook can be more readable
- `.gitignore`: A hidden file that tells git to not track certain files and folders
>>>>>>> 31c14d8fe12f902e31d318d489468ead4d3a8847
