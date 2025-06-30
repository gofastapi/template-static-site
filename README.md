# template-static-site

1. Install serverless
2. Run `npm i` to install the serverless plugins and your project dependencies
3. Set up your AWS credentials in github secrets. Checkout the github workflow file for the secret names
4. Run `npx sls deploy --stage=prod`

Github pipeline is setup to be triggered when code changes are merged to the main branch. Basic setup is already included in the workflow yaml file, you can update it if necessary.

