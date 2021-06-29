# Getting Started With Schematics

This repository is a basic Schematic implementation that serves as a starting point to create and publish Schematics to NPM.

## Workflow

```txt
npm run build
```

## Setting up this project

```txt
>npm install -g @angular-devkit/schematics-cli
>cd my-component
>schematics blank --name=my-component
CREATE my-component/package.json (569 bytes)
CREATE my-component/README.md (639 bytes)
CREATE my-component/tsconfig.json (656 bytes)
CREATE my-component/.gitignore (191 bytes)
CREATE my-component/.npmignore (64 bytes)
CREATE my-component/src/collection.json (231 bytes)
CREATE my-component/src/my-component/index.ts (318 bytes)
CREATE my-component/src/my-component/index_spec.ts (503 bytes)
√ Packages installed successfully.
```

## Original Readme

### Testing

To test locally, install `@angular-devkit/schematics-cli` globally and use the `schematics` command line tool. That tool acts the same as the `generate` command of the Angular CLI, but also has a debug mode.

Check the documentation with
```bash
schematics --help
```

### Unit Testing

`npm run test` will run the unit tests, using Jasmine as a runner and test framework.

### Publishing

To publish, simply do:

```bash
npm run build
npm publish
```

That's it!
