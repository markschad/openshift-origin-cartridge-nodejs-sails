OpenShift NodeJS & SailsJS Cartridge
====================================

This cartridge provides [node.js](http://nodejs.org/) support to an OpenShift gear and builds a template [sails.js](http://sailsjs.org/) application.

## Installation

### Web Application

The simplest way to install this cartridge is from the [OpenShift Web Application](https://openshift.redhat.com/app/console/application_type/custom?unlock=true&application_type%5Bcartridges%5D=https://raw.github.com/markschad/openshift-origin-cartridge-nodejs-sails/master/metadata/manifest.yml).  Simply enter a name for your application and click Create Application!

### Command Line

If you have [rhc](https://www.openshift.com/developers/rhc-client-tools-install) installed you can run the following command.  This will also copy the template source to your working directory and add the upstream remote.  This is the fastest way to get a new sails template up and running on OpenShift.

```bash
rhc app-create mysails https://raw.github.com/markschad/openshift-origin-cartridge-nodejs-sails/master/metadata/manifest.yml```

## About

This cartridge is based on the latest (0.10) OpenShift Online NodeJS cartridge.  In order to allow Sails to run without naturally on the gear a small modification was made to the _control start_ command in order to force supervisor to ignore sail's .tmp directory.

More information about the NodeJS cartridge can be found [here](http://openshift.github.io/documentation/oo_cartridge_guide.html#nodejs).

## Questions or Comments

Feel free to email me. mark.schad@gmail.com
