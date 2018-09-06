# File and Folder Guide

Please follow this guide before: 
* creating GitHub repository
* creating Google Drive folder related to GitHub repository

## Names

### GitHub Repository Name

Name Format: `Name = prefix + sender + receiver` or `Name = prefix + functionality`

**Team Name: Prefix (<= 6 letters)**

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

Examples: `hr-lawson-cigna`, `ac-concur-costpoint`, `tech-inventory`, `cewa-nigeria-2019`…

### Google Drive Folder Name

Name Format: `Name = PREFIX + TECHNOLOGY + Purpose`

Examples: `HR JS Outputs`: Human Resources' Javascript outputs, `AC JS Outputs`: Accounting's Javascript outputs...

## Structure

### Github Folder Structure

Depends on the project.
* If `config` file is inside project folder, remember to include *config* in `.gitignore` file.
* If `config` file is outside project folder, name the config file `GitHub repo + config`. E.g.: `hr-concur-cospoint-config.js`, `tech-inventory-config.json`...