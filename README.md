# AWS Serverless REST API using Go
AWS Serverless REST API using Go, API Gateway and AWS Lambda

## How to use
### Build go code
1. Check that you are in the correct directory, as this is where main.go is located.
    ```
    cd cmd
    ```
2. Build the project code, and move the output file to build directory.
    ```
    go build main.go
    ```
3. Make the zip file of the main.exe and store it in build directory.
4. Create a Lambda Function in AWS Management Console.
5. Create DynamoDB with "LambdaGoUser" as tableName and email as primary key.

`
curl --header "Content-Type: application/json" --request POST --data '{"email":"parth@gmail.com","firstName":"Parth","lastName":"Shah"}' https://xz6z484apg.execute-api.us-east-1.amazonaws.com/staging
`
