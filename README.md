# TG-repository

Repository for TG groups.

## Test

Start local DynamoDB:

`sls dynamodb start --migrate`

Run a simple GraphQL call:

`serverless invoke local --function graphql --path tests/fixtures/hello.json`
