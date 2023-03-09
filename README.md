# Serverless Data Engineering Pipeline
## Hello World Build and Deploy

1.  `sam init`
2.  `sam build`
3.  `sam deploy --guided`

## Deploy and Testing (Key Concepts)

Test two ways:  

`sam local invoke`
`sam local start-api`

Then curl `curl http://127.0.0.1:3000/hello`

* API Gateway
* CloudWatch Logs
* IAM Security settings

