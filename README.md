<h1 align="center">
  <a href="https://www.ndi.org/"><img src="https://www.ndi.org/sites/all/themes/ndi/images/NDI_logo_svg.svg" alt="NDI Logo" width="200"></a>
</h1>

<h1 align="center">
  NDI Tech's Standards for GitHub
</h1>

<p align="center">
  <a href="#github-policies">Policies</a> - 
  <a href="#documentation">Documentation</a> - 
  <a href="#style-guide">Style</a> - 
  <a href="#readme-format">Readme</a> - 
  <a href="#readme-samples">Sample(s)</a>
</p>

This repository is used for NDI Tech Team's standardized **readme files**, **documentation**, **style guide** and **GitHub policies**.

## GitHub Policies

* Follow [Collaborator Access Guide](./collaborator-access.md) before giving NDI Tech GitHub access to vendors, consultants, freelancers and contributors.
* Please follow [File and Folder Guide](./file-folder.md) before creating GitHub repository and Google Drive folder.

## Documentation

* > "Write the documentation so that the 2nd developer can explain the repository to the 3rd one."

## Style Guide

* When commit code, follow [Code Commit Guide](./code-commit.md).
* When working with Javascript and or React project, follow Google's [Javascript Style Guide](https://google.github.io/styleguide/jsguide.html) and Airbnb's [React Style Guide](https://github.com/airbnb/javascript/tree/master/react).
* Some old projects did not follow this standard but this applies to new ones (from September 2018).
* Keys:
    * Use `all-lower-case-file-name.js` except in React folders, `ReactComponent` (PascalCase) and `reactProjectFile.js` (camelCase). 
    * Use semicolon to close statements, except function and class declarations.

## Readme Format

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

## Readme Samples

* [Standard Script Readme File](./script.md)