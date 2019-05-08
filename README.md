Shrtnr API Docs
===============

The API documentation for Shrtnr are provided as an OpenApi 3.0 spec. This repo
also includes a package.json file that will provide a development webserver that
will use the [RapiDoc](https://mrin9.github.io/RapiDoc/) viewer to render the 
spec in a web browser.

These docs are also available at: https://shrtnr.github.io/api-docs


Running Locally
---------------

Assuming Node and NPM are already installed, follow these steps:

```
npm install
npm start
```

This will start a local web server and display the url to use to access the
RapiDoc viewer.


Linting with Speccy
-------------------

Additionally, the package.json imports the [Speccy](https://github.com/wework/speccy) 
OpenAPI linter to check for defects in the schema.

These results can be viewed once by running:

```
npm run lint
```

Watching for Changes
====================

To have npm-watch monitor for file changes and automatically re-run the linter
or restart the webserver, kick it off with:

```
npm run watch
```
