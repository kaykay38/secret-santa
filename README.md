In this assignment we are going to create some automated web tests as well as convert Gifts screens to use AlpineJS instead of the MVC model

- Using PlaywrightSharp, automate the following items of the website
  - Verify that when landing on the homepage, Secret Santa is displayed in the navigation banner ✔❌
  - Verify that all 3 pages (Users, Groups, Gifts) can be reached via clicking on the navigation elements ✔❌
  - Create a Gift (should assert that the number of gifts after the creation is one greater than the number of gifts before the user was created) ✔❌
  - Modify the last gift in the list (should assert that the updated data was successfully saved/displayed to the screen) ✔❌
  - Delete the last gift in the list (should assert that the number of gifts after the delete is one less than the number of gifts before the deletion) ✔❌
  - All of these tests should be able to be executed without having to manually start the Web and Api projects ✔❌
- Using AlpineJS, convert the CRUD pages for Users to be javascript based instead of MVC based
  - Index page should fetch the Users via javascript directly from the API ✔❌
  - Create page should submit the Users information via javascript directly to the API. Upon successful save, the user should be redirected back to the Users index page ✔❌
  - Edit page should submit the Users information via javascript directly to the API. Upon successful update, the user should be redirected back to the Users index page ✔❌
  - Delete opration should submit the request directly to the API via javascript and then refresh the Index page via a javascript call directly to the API ✔❌
﻿

[![Build And Test](https://github.com/kaykay38/EWU-CSCD379-2021-Spring/actions/workflows/BuildAndTest.yml/badge.svg)](https://github.com/kaykay38/EWU-CSCD379-2021-Spring/actions/workflows/BuildAndTest.yml)
[![Deployment](https://github.com/kaykay38/EWU-CSCD379-2021-Spring/actions/workflows/Deployment.yml/badge.svg)](https://github.com/kaykay38/EWU-CSCD379-2021-Spring/actions/workflows/Deployment.yml)
[![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://cscd379-secret-santa-mia.azurewebsites.net)

Website: https://cscd379-secret-santa-mia.azurewebsites.net

Repo: https://github.com/kaykay38/EWU-CSCD379-2021-Spring/tree/Assignment6
