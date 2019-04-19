# File and Folder Guide

Please follow this guide before: 
* creating GitHub repository
* creating Google Drive folder related to GitHub repository

## Names

### GitHub Repository Name

Name Format: 
```
Name = prefix + sender + receiver
Name = prefix + functionality + year
Name = functionality + year

For multi-function/multi-partner
Name = brand + data

GOOD: hr-lawson-cigna, ac-concur-costpoint, tech-inventory, cewa-nigeria-2019
BAD: ndi-inventory
```
* Team Name: Prefix (<= 6 letters)
* DO NOT: include `ndi` in the name since this is NDI's GitHub, adding `ndi` doesn't help when searching for repositories.

Administrative Teams:
* Accounting: `ac-`
* Human Resources: `hr-`
* Technology: `tech-`

Regional Teams (NDI regional team acronyms: Asia/CEE/CEWA/Eurasia/LAC/MENA/SEA)
* Asia: `asia-`
* Central & Eastern Europe: `cee-`
* Central & West Africa: `cewa-`
* Latin America & the Caribbean: `lac-`
* Middle East & North Africa: `mena-`
* Southern & East Africa: `sea-`

### Google Drive Folder Name

Name Format:
```
Name = PREFIX + TECHNOLOGY + Purpose

GOOD:
HR JS Outputs // Human Resources' Javascript outputs.
AC JS Outputs // Accounting's Javascript outputs.
Test // Test folder can contain several sub-folders.
BAD:
Production // So many Production folders by many teams. It's important to easily find the production folder for each project.
```

## Structure

### Github Folder Structure

Depends on the project.
* If `config` file is inside project folder, remember to include *config* in `.gitignore` file.
* If `config` file is outside project folder, name the config file `GitHub repo + config`. E.g.: `hr-concur-cospoint-config.js`, `tech-inventory-config.json`...
