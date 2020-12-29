# 24-Hour-Video
A Serverless video-sharing website, a YouTube mini clone

Instructions for Deployment
---
- Replace  `PipelineId` with your Transcoder Pipeline ID in `index.js`
- Replace the lambda function ARN in `package.json` deploy script
- `npm install`
- `npm run deploy`



Notes
---

- For enabling the `s3.putObjectAcl` function to change ACL of S3 objects, we should enable objects to be public in the bucket permissions.





Issues
---
- In case `npm test` doesn't work properly when tested locally, install `run-local-lambda` package globally, as `npm install -g run-local-lambda`
