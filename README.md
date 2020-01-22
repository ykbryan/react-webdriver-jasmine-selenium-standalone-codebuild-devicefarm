yarn add chai webdriverio --dev
yarn add @wdio/selenium-standalone-service --dev
yarn add selenium-standalone --dev
yarn add jasmine --dev
yarn add @wdio/jasmine-framework --dev
yarn add wdio-spec-reporter --dev

npm install -g wdio

yarn add @wdio/cli --dev

node_modules/.bin/wdio run wdio.conf.js

https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-profiles.html
export AWS_DEFAULT_REGION=us-west-2
export AWS_PROFILE=defaultoregon

https://docs.aws.amazon.com/devicefarm/latest/testgrid/testing-frameworks-nodejs.html
aws devicefarm list-projects

Refer to buildspec-test.yml for commands
Or refer to https://testgrid-devicefarm.us-west-2.amazonaws.com/

Attach IAM permission to codebuild, allow device farm commands
