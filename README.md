# Standardized README

Standardized README.md files and documentation

## List of samples

* [Standard Script Readme File](./script.md)

## README.md Format

* NDI logo (looks nice)
* Name of the Repo/Script/App
* List of important stuff: license... (currently not using distributed continuous integration services like Travis or circleci)
* List of Headings: makes it easier to navigate in long file.
* Documentation: guide to use and to troubleshoot.
* Testing: guide to do tests.
* Installation: guide so users can run the app.
* Contributing: guide for other developers in the future.
* License: best practice to include license, however this can be omitted.
* Author(s)

## File and Folder Guide

:warning: Please follow [File and Folder Guide](./file-folder.md) before creating GitHub repository and Google Drive folder.

## Style Guide

* When commit code, follow [Code Commit Guide](https://github.com/nditech/git-styleguide/blob/gh-pages/README.md).
* When working with Javascript and or React project, follow Google's [Javascript Style Guide](https://google.github.io/styleguide/jsguide.html) and Airbnb's [React Style Guide](https://github.com/airbnb/javascript/tree/master/react).
* Some old projects did not follow this standard but this applies to new ones (from September 2018).
* Keys:
    * Use `all-lower-case-file-name.js` except in React folders, `ReactComponent` (PascalCase) and `reactProjectFile.js` (camelCase). 
    * Use semicolon to close statements, except function and class declarations.