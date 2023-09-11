##

npm i json-server
npm i -D json-server-auth

###

Create db.json file with mock data.

###

Start JSON server (with JSON server Auth as middleware) :
json-server db.json -m ./node_modules/json-server-auth

<!-- ###

Fire server: json-server --watch db.json -->

###

More info:
https://www.npmjs.com/package/json-server

###

to use authorization add json-server-auth
https://www.npmjs.com/package/json-server-auth

######

db.json - "auth" replaced with "users" at the top of the file
