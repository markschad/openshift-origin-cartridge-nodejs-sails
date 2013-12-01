OpenShift NodeJS & SailsJS Cartridge
====================================

This cartridge provides NodeJS support to an OpenShift gear and builds a template SailsJS application.

## Usage

### Web Application

The simplest way to install this cartridge is from the [OpenShift Web Application](https://openshift.redhat.com/app/console/application_type/custom?unlock=true&application_type%5Bcartridges%5D=https://raw.github.com/markschad/openshift-origin-cartridge-nodejs-sails/master/metadata/manifest.yml).  Simply enter a name for your application and click Create Application!

### Command Line

If you have [rhc](https://www.openshift.com/developers/rhc-client-tools-install) installed you can run the following command.

```bash
rhc app-create mysails https://raw.github.com/markschad/openshift-origin-cartridge-nodejs-sails/master/metadata/manifest.yml
```

## Further Reading

[node.js](http://nodejs.org/)
[sails.js](http://sailsjs.org/)
[Openshift Cartridge Guide](http://openshift.github.io/documentation/oo_cartridge_guide.html#nodejs).