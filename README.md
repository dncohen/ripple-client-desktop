# Desktop Client

## Build and test

~~~
npm install
cp config-example.json config.json
cp src/js/config-example.json src/js/config.js

# If you want to build executable:
mkdir -p build/packages

# If grunt not installed globally:
npm install grunt-cli

# Compile
./node_modules/.bin/grunt

# Run debug version:
npm install nw
./node_modules/.bin/nw build/bundle/nw-desktop-debug
~~~
