# Presentations of Mitchell Herrijgers

Presentations can be found online at: http://morlack-presentations.s3-website-eu-west-1.amazonaws.com/

## Local dev

To run it locally, run:

```
npm install
npm start
```

Now you can view the presentations by selecting one from the list

## Deploying to S3
```bash
aws s3 cp ./ s3://morlack-presentations/ --recursive
```