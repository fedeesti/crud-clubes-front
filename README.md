# CRUD-CLUBES-FRONT

Frontend of the application that allows users to perform CRUD (Create, Read, Update, and Delete) operations of soccer teams.

This application is built with:
- React.js
- Typescript
- Formik
- Yup (validations)
- Cypress (E2E Testing)

## LINK

https://crud-clubs-frontend.vercel.app/

## Installation Instructions

- Download the repository on your computer
- [Instalar Yarn](https://yarnpkg.com/lang/en/docs/install)
- Run yarn install to install the dependencies
- Create `.env` file in the root of your project by adding the following variable names:
     - VITE_URL_API_BASE=https://crud-clubs.up.railway.app/api/v1/teams
     - URL_APP_BASE= (localhost proposed by your computer)
     - VITE_GOOGLE_API_KEY= (create a key at https://console.cloud.google.com/google/maps-apis/credentials )
- To run the application, run `yarn dev`. When running this command, the application will be executed through VITE, with which the server will restart when detecting changes.
- To run the tests, run `yarn cy:open`