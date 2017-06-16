# judo-heroes
Probably ending up being a 1-to-1 copy of the tutorial project

<strong>To build from root folder:</strong>*
set NODE_ENV=production | node_modules/.bin/webpack -p

<strong>To start app using http-server:</strong>
node_modules/.bin/http-server src/static

<strong>To start app using node.js server:</strong>
set NODE_ENV=production | node_modules/.bin/babel-node --presets react,es2015 srv/server.js

*: These are for Windows. Running on Linux, you remove the 'set' and the pipe ('|')
