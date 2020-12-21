# serverless-stack-api
Project built using AWS &amp; the serverless-stack.

--- 

##### Handler.js : file contains actual code for the services/functions that will be deployed to AWS Lambda.
##### serverless.yml : file contains the configuration on what AWS services Serverless will provision and how to configure them.

### Plugins:
- `serverless-bundle`  : This plugin supports ES6 and TypeScript,reduces extra config by keeping only 1 dependency
- `serverless-offline` : This Serverless plugin emulates AWS λ and API Gateway on your local machine to speed up your development cycles. To do so, it starts an HTTP server that handles the request's lifecycle like APIG does and invokes your handlers
- `serverless-dotenv-plugin` : This plugin allows you to reference envt variables into Serverless as ${env:VAR_NAME} inside your config and it will load them into your lambdas

