#AWS Serverless REST API using Go
This is a project where I built and hosted an entire serverless stack using AWS lambda function, Golang and DynamoDB


Use this to get info from API:
`
curl --header "Content-Type: application/json" --request POST --data '{"email":"parth@gmail.com","firstName":"Parth","lastName":"Shah"}' https://xz6z484apg.execute-api.us-east-1.amazonaws.com/staging
`
