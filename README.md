# biz-basic-plugins

This repo contains two basic plugins for the Business API Ecosystem. In particular, this repo contains the basic-url
data type that allows the creation of URL digital products, and the basic-file plugin that allows the creation of
products where it is offered a digital file.

Both plugins are minumum definitions and no asset validation is done. Nevertheless, these plugins can be used for
testing or as the starting point for the development of a more complex one.

## Installation

The first step for installing these plugins is including them in a zip file:

```
zip basic-url.zip package.json basic_url.py
```

```
zip basic-file.zip package.json basic_file.py
```

Then, load the plugins into the platform using the *loadplugin* command of the Business Ecosystem Charging Backend

```
./manage.py loadplugin /path/to/your/plugin/basic-url.zip
```

```
./manage.py loadplugin /path/to/your/plugin/basic-file.zip
```
