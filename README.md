# Getting Started

Welcome to CapEx project for source code of Capital Expenditure Approval Process Live Process Package.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`User Interface/` | source code for Task UI project here
`VisibilityActionWorkflow/` | source code for WOrkflow project here




## Learn More

Learn more at https://github.com/SAP-samples/cloud-workflow-samples/tree/master/cf-capitalexpenditure-lp




## Command Guide

```vim
npm config list
npm config delete @sap:registry -u

npm install -g hana-cli
hana-cli version
cds version
npm i -g @sap/cds-dk

cds init hana_app --add hana,mta,pipeline

npm install
cds build
hana-cli createModule

cf services
cf create-service hana hdi-shared hana_app-db
cf create-service-key hana_app-db default
hana-cli serviceKey hana_app-db default
cp ./default-env.json ./db/default-env.json && cp ./default-env.json ./srv/default-env.json

npm run env
hana-cli status
hana-cli systeminfo

cd db
npm install
npm start

hana-cli opendbx
```