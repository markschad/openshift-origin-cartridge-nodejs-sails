OpenShift NodeJS & SailsJS Cartridge
====================================

This cartridge provides NodeJS support to an OpenShift gear and builds a template SailsJS application.

## Usage

### Web Application

From the OpenShift Online web application you may install this gear from the following URL.

```
https://raw.github.com/markschad/openshift-origin-cartridge-nodejs-sails/master/metadata/manifest.yml
```

### Command Line

If you have [rhc](https://www.openshift.com/developers/rhc-client-tools-install) installed you can run the following command.

```bash
rhc app-create mysails https://github.com/markschad/openshift-origin-cartridge-nodejs-sails/archive/master.zip
```

## Further Reading

[node.js](http://nodejs.org/)
[sails.js](http://sailsjs.org/)
[Openshift Cartridge Guide](http://openshift.github.io/documentation/oo_cartridge_guide.html#nodejs).