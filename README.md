# 24-Hour-Video
A Serverless video-sharing website, a YouTube mini clone

Instructions for Deployment
---
- Replace  `PipelineId` with your Transcoder Pipeline ID in `index.js`
- Replace the lambda function ARN in `package.json` deploy script
- `npm install`
- `npm run deploy`





Issues
---
- In case `npm test` doesn't work properly when tested locally, install `run-local-lambda` package globally, as `npm install -g run-local-lambda`
