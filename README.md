## Deploy the Backend

`cd backend`
`npm update --save`
`npm audit fix`
For the first time, create an application in your org in Serverless portal
`serverless`
Next time, deploy the app and note the endpoint url in the end
`serverless deploy --verbose`
If you face a permissions error, you may need to specify the user profile
`sls deploy -v --aws-profile serverless`

## Configure the Frontend

Set apiId and Auth0 parameters in the config.ts file in the client folder.

## Run the Frontend

`cd client`
`npm update --save`
`npm audit fix --legacy-peer-deps`
`npm install --save-dev`
`npm run start`
