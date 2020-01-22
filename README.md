yarn add chai webdriverio --dev
yarn add @wdio/selenium-standalone-service --dev
yarn add selenium-standalone --dev
yarn add jasmine --dev
yarn add @wdio/jasmine-framework --dev
yarn add wdio-spec-reporter --dev

npm install -g wdio

yarn add @wdio/cli --dev

node_modules/.bin/wdio run wdio.conf.js

https://docs.aws.amazon.com/devicefarm/latest/testgrid/testing-frameworks-nodejs.html
export AWS_REGION=us-west-2
export AWS_PROFILE=defaultoregon
aws devicefarm list-projects

Refer to buildspec-test.yml for commands

Attach IAM permission to codebuild, allow device farm commands
