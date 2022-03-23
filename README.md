# Camunda Modeler plugin starter

[![Compatible with Camunda Modeler version 5.0](https://img.shields.io/badge/Camunda%20Modeler-5.0+-blue.svg)](https://github.com/camunda/camunda-modeler)	[![Plugin Type](https://img.shields.io/badge/Plugin_Type-BPMN-orange.svg)](#) [![Plugin Type](https://img.shields.io/badge/Plugin_Type-Styles-orange.svg)](#)

## About
This boilerplate serves as a starting point for creating your own plugin for the [Camunda Modeler](https://github.com/camunda/camunda-modeler), based on the [plug-in example](https://github.com/camunda/camunda-modeler-plugin-example), and makes you able to directly test your own modules, bootstrapping a development setup that spawns a small webserver and rebuilds your app on changes run.

## Development Setup

Use [npm](https://www.npmjs.com/), the [Node.js](https://nodejs.org/en/) package manager to download and install required dependencies.

To make the Camunda Modeler aware of your plug-in you must link the plug-in to the [Camunda Modeler plug-in directory](https://docs.camunda.io/docs/components/modeler/desktop-modeler/plugins/#plugging-into-the-camunda-modeler) via a symbolic link.
Available utilities to do that are [`mklink /d`](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/mklink) on Windows and [`ln -s`](https://linux.die.net/man/1/ln) on MacOS / Linux.

Re-start the app in order to recognize the newly linked plug-in.

## Building the project

Install all required dependencies, run:

```sh
npm install
```

Build the project via

```sh
npm run all
```
to create the sample distribution in both `dist` (for the Camunda Modeler plugin) and `public` (for the development setup)

To bootstrap the development setup, spawning the small webserver mentioned before, run:

```sh
npm run dev
```

## Additional Resources

* [Plugins documentation](https://docs.camunda.io/docs/components/modeler/desktop-modeler/plugins)
* [Camunda Modeler examples](https://github.com/camunda/camunda-modeler-plugins)
* [Properties panel extension](https://github.com/bpmn-io/bpmn-js-examples/tree/master/properties-panel-extension)
* [Our Multi-diagram plugin](https://github.com/sharedchains/camunda-modeler-plugin-multidiagram)

## License

MIT
