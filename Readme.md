# Create Module Boilerplate

The easiest way to create your own npm modules.

### Installation
```sh
$ git clone https://github.com/scaki/create-module-boilerplate.git
```

### Simple Using

To start using hot reloading
```sh
$ npm start
```

To create the module only
```sh
$ npm build
```

### Customize
You can customize your settings by changing the settings in `package.json`

```sh
  "name": "create-module-boilerplate",
  "version": "1.0.0",
  "description": "",
  "author": "Safa ÇAKI",
  "license": "ISC",
  "repository": {
    "type": "git",
    "url": "git+https://github.com/scaki/create-module-boilerplate.git"
  }
```

To use the external package, enter the package names in the field below
`webpack.config.js`

```sh
    externals: ['react'],
```
