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
- There are breaking changes in the c++ API when using node version 4. You should use node version 0.12. <-- Still true?  Seems to build OK with node v4.7.3
- The current package.json specifies ripple-lib 0.13.0-rc14 because rc15 has breaking changes.  Which is unusual slip in there without even a version change, but that happened.
- Pathfinding on the send page comes up empty for certain amounts.  Annoying.

