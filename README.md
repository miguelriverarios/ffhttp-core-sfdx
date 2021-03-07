# Apex HTTP Callout Framework - SFDX Project for Unlocked Packages

<a href="https://githubsfdeploy.herokuapp.com?owner=miguelriverarios&repo=ffhttp-core-sfdx">
    <img alt="Deploy to Salesforce"
        src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png">
</a>

This repo is an offshot of the amazing [ffhttp-core](https://github.com/financialforcedev/ffhttp-core) by the folks over at [FinancialForce for Developers](https://github.com/financialforcedev). The purpose of this repo is simply to prove the same framework for making HTTP Callouts via an Unlocked Package, so that it plays nice in the new ecosytem.

Instead of forking the repo, I deployed the project to one of my DevHubs and then pulled the classes and labels into an SFDX project, so I believe I've lost some of GitHub's automatic comparison between the main branch and this branch. That being said, the core code remains unchanged as of March 6, 2021 and should be caught up with the main branch. The original repo has been stable and idle for ~4 years, so I don't see any issue with this project being out of sync with the original branch any time soon, but I can't guarantee that I will keep up with future updates made to the original repo.

Everything below this point comes from the README of the original repo for your convenience, except I've redirected the issues to this repo.

## Introduction

An Apex framework has been created to provide functionality for HTTP callouts. This **Core** library has been extended by five libraries [Google Cloud Print](https://github.com/financialforcedev/ffhttp-googlecloudprint), [Google Drive](https://github.com/financialforcedev/ffhttp-googledrive), [Google Mirror](https://github.com/financialforcedev/ffhttp-googlemirror), [Google Sheets](https://github.com/financialforcedev/ffhttp-googlesheets) and [Dropbox](https://github.com/financialforcedev/ffhttp-dropbox).

The **Google Cloud Print** library extends the **Core** library to provide access to Google Cloud Print API calls found at [Cloud Print](https://developers.google.com/cloud-print/).

The **Google Drive** library extends the **Core** library to provide access to Google Drive API calls found at [Google Drive](https://developers.google.com/drive/v2/reference/).

The **Google Mirror** library extends the **Core** library to provide access to Google Mirror API calls found at [Google Mirror](https://developers.google.com/glass/v1/reference/).

The **Google Sheets** library extends the **Core** library to provide access to Google Sheets API calls found at [Google Sheets](https://developers.google.com/google-apps/spreadsheets/).

The **Dropbox** library extends the **Core** library to provide access to Dropbox API calls found at [Dropbox](https://www.dropbox.com/developers/core/docs).

Sample applications have been created for the [Core](https://github.com/financialforcedev/ffhttp-core-samples), [Google Cloud Print](https://github.com/financialforcedev/ffhttp-googlecloudprint-samples), [Google Drive](https://github.com/financialforcedev/ffhttp-googledrive-samples), [Google Mirror](https://github.com/financialforcedev/ffhttp-googlemirror-samples), [Google Sheets](https://github.com/financialforcedev/ffhttp-googlesheets-samples)) and [Dropbox](https://github.com/financialforcedev/ffhttp-dropbox-samples) libraries to demonstrate the use of this library within Salesforce.

## Key Features

- Framework for HTTP callouts.
- JSON serialization and deserialization base classes.
- OAuth Client - extends the base AbstractClient to provide the callouts required for OAuth authentication.

## Reporting Issues & Enhancements

Please report any issues using the github [issues](https://github.com/miguelriverarios/ffhttp-core-sfdx/issues) feature. Suggestions / bug reports are welcome as are extensions containing additional functionality.
