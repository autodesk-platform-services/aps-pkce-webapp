# APS-PKCE-WEBAPP

# THIS IS A WORK IN PROGRESS

## Introduction

The purpose of this sample is demonstrate a quick way to test and obtain your three legged tokens using PKCE method in the context of a single page app (you can refer [here](https://aps.autodesk.com/en/docs/oauth/v2/tutorials/get-3-legged-token-pkce/) for more details).

## Why PKCE?

As said by [Petr Broz](https://github.com/petrbroz) in [this blog post](https://aps.autodesk.com/blog/new-application-types):

>This option is recommended for scenarios where your application is running natively on a desktop or a mobile device, in other words, for scenarios where you cannot protect your app's credentials. This application type uses Proof Key for Code Exchange (PKCE) for increased security.

## How it works?

We need to basically cover the workflow below:

![thumbnail](./assets/desktop-mobile-spa1.png)

This sample is based in the code wrote by [Petr Broz](https://github.com/petrbroz) in [this blog post](https://aps.autodesk.com/blog/new-application-types).

You can basically type your own client id at https://joaomartins-callmejohn.github.io/PKCE-TEST/ and start the process to get your token.
