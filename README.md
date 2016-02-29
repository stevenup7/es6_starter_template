# ES6 with require javascfript template project

Assumes and app.js in src folder as base for project.

## Building the Project

```bash
npm run build
```

this will call several other npm scripts
 * browserify - for require
 * babel - build es6 to es2015
 * build_cleanup - remove working files

### Autobuilding project

```bash
npm run watch
```