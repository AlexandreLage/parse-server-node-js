Follow this procedure for fixing npm permissions:
https://docs.npmjs.com/getting-started/fixing-npm-permissions


Follow this script to install parse-server on a new machine:
https://docs.parseplatform.org/parse-server/guide/

$ sh <(curl -fsSL https://raw.githubusercontent.com/parse-community/parse-server/master/bootstrap.sh)
$ npm install -g mongodb-runner
$ mongodb-runner start
$ npm start


Follow this script to install parse-dashboard:

$ npm install -g parse-dashboard
$ parse-dashboard --appId N5HzTm2AikuVlrTLHwh5NnPcKDHUgcFXQJC7enzX --masterKey bsEwHN6VKNvOkNPcaBm7Ianxz4A2AVm0y3WBBti8 --serverURL "http://localhost:1337/parse" --appName TC
