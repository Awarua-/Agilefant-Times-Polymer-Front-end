## Agilefant Times front end

> A front end for the [AgilefantTimes](https://github.com/mrkno/AgilefantTimes) repository. 
Built using Polymer 1.0

This project is based on the [Polymer starter kit](https://github.com/PolymerElements/polymer-starter-kit)
 
:sparkles: [Live demo](http://times.sws.nz) :sparkles:

### Install dependencies

#### Quick-start (for experienced users)

With Node.js installed, run the following one liner from the root folder:

```sh
npm install -g gulp bower && npm install && bower install
```

#### Prerequisites (for everyone)

Agilefant time front end requires the following major dependencies:

- Node.js, used to run JavaScript tools from the command line.
- npm, the node package manager, installed with Node.js and used to install Node.js packages.
- gulp, a Node.js-based build tool.
- bower, a Node.js-based package manager used to install front-end packages (like Polymer).

**To install dependencies:**

1)  Check your Node.js version.

```sh
node --version
```

The version should be at or above 0.12.x.

2)  If you don't have Node.js installed, or you have a lower version, go to [nodejs.org](https://nodejs.org) and click on the big green Install button.

3)  Install `gulp` and `bower` globally.

```sh
npm install -g gulp bower
```

This lets you run `gulp` and `bower` from the command line.

4)  Install the local `npm` and `bower` dependencies.

```sh
cd AgilefantTimesFrontEnd && npm install && bower install
```

This installs the element sets (Paper, Iron, Platinum) and tools the agilefant times front end requires to build and serve apps.

### Development workflow

#### Serve / watch

```sh
gulp serve
```

This runs the unit tests defined in the `app/test` directory through [web-component-tester](https://github.com/Polymer/web-component-tester).

#### Build & Vulcanize

```sh
gulp
```
