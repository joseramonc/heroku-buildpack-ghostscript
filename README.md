# Heroku Buildpack for Ghostscript

Currently installs Ghostscript 10.01.2 on Heroku Cedar.

## Install

Add the buildpack to your app.json [as described here](https://devcenter.heroku.com/articles/app-json-schema#buildpacks):

E.g.,

```
  "buildpacks": [
    { "url": "https://github.com/Manifestly/heroku-buildpack-ghostscript" },
    { "url": "heroku/ruby" }
  ],

```
