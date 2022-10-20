# helloworld_googlecloudfunction
Sample hello world node project for google cloud function

## Installation
```bash
npm install
```

## Deployment to GCP
```bash
gcloud functions deploy ulan-helloHttp --runtime nodejs16 --trigger-http 
```

## Testing the Function
```bash
gcloud functions describe ulan-helloHttp
```

## Link to Google's example
https://cloud.google.com/functions/docs/create-deploy-http-nodejs
