# Avixi-Tools

![Platforms](https://img.shields.io/badge/platform-Windows-lightgray.svg)

![Autodesk Revit 2020](https://img.shields.io/badge/Autodesk Revit-2020-blue.svg)


### Website

[https://www.avixi.com/](https://www.avixi.com/)

# Setup

1. **Installation**: Run Avixi .exe files.

### Troubleshooting

Setup an Autodesk Forge Account and create an app.
Note down your client id and secret for deployment.
Set the callback url as `https://**YOURURL.com**/api/forge/callback/oauth`

### BIM 360 Setup

Have a BIM 360 account with projects in it.
Request access through Autodesk for the ability to add Custom Integrations.
Add a custom integration and input the client id and app name from your forge app

![Custom Integration Setup](/DashboardSetup.png)

## Deployment

To deploy this application to Heroku, the **Callback URL** for Forge must use your `.herokuapp.com` address. After clicking on the button below, at the Heroku Create New App page, set your Client ID, Secret and Callback URL for Forge.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Watch [this video](https://www.youtube.com/watch?v=Oqa9O20Gj0c) on how deploy samples to Heroku.

## Packages used

All Autodesk Forge NPM packages are included by default, see complete list of what's available at [NPM website](https://www.npmjs.com/browse/keyword/autodesk). OAuth, Model Derivative and OSS are used. Some other non-Autodesk packaged are used, including [express](https://www.npmjs.com/package/express) and its session/cookie middlewares ([express-session](https://www.npmjs.com/package/express-session) and [cookie-parser](https://www.npmjs.com/package/cookie-parser)) for user session handling. The front-end uses [bootsrap](https://www.npmjs.com/package/bootstrap) and [jquery](https://www.npmjs.com/package/jquery).

## Tips & tricks

- Hover over charts to display more data and click to examine data further

## Documentation

- [BIM 360 API](https://developer.autodesk.com/en/docs/bim360/v1/overview/) and [App Provisioning](https://forge.autodesk.com/blog/bim-360-docs-provisioning-forge-apps)
- [Data Management API](https://developer.autodesk.com/en/docs/data/v2/overview/)
- [Viewer](https://developer.autodesk.com/en/docs/viewer/v6)
- [Forge Developer Portal](http://developer.autodesk.com/)

## Written by

Codey Van Ourkerk & Joey Smith <br />
<a href="http://avixi.com/">Avixi</a> <br />
