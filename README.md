# Desktop Client

## Install Dependencies

- Fork and clone the ripple-client-desktop repository 
- Run `npm install`

## Build

- In the ripple-client-desktop repository, make a copy of the `config_example.js` file and name it `config.js`
- Run `./node_modules/.bin/gulp` in your command line for development
  
- Run `./node_modules/.bin/gulp packages` in your command line for the production ready client
- Your desktop client is in the `packages/RippleAdminConsole-<version>` directory

### Note
- Builds on node.js v4.7.3
- The current package.json specifies ripple-lib 0.13.0-rc14 because rc15 introduced breaking changes (!)
- The send page has a bug preventing it from calculating a source amount of XRP, for many destination currencies and values.


