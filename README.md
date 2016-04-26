# site-recipes-kinto

This is an experimental admin console for managing Firefox [site recipes](https://dxr.mozilla.org/mozilla-central/source/toolkit/components/passwordmgr/content/recipes.json) data using [Kinto](http://kinto-storage.org/).

## Demo

![](http://i.imgur.com/RfkmVuT.png)

A live demo is hosted [on gh-pages](https://mozilla-services.github.io/site-recipes-kinto).

Settings should be configured as following:

![](http://i.imgur.com/MvfsnVl.png)

Then click on the *site-recipes* link in the sidebar, and press the *Synchronize* button.

Published JSON data are retrievable using [this url](https://public:notsecret@kinto.dev.mozaws.net/v1/buckets/default/collections/experiments/records).

## Install

```
$ git clone https://github.com/mozilla-services/site-recipes-admin.git
$ npm install
```

## Run localy

```
$ npm start
```

Then head to [localhost:3000](http://localhost:3000/).

## License

Apache-2.0
