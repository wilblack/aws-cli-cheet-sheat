# aws-cli-cheet-sheat
A cheat sheet for AWS CLI commands

You can specify the AWS Credentials prodile to use with the `--profile <PROFILE_NAME>` option.

## DynamoDB

`aws dynamodb help`

`aws dynamodb list-tables`

## EC2

`aws ec2 describe-instances`

## IAM

`aws iam help`

`aws iam list-users`


## S3 

Delete an empty bucket `aws s3api delete-bucket --bucket <bucket-name>`

Delete a bucket and all objects in it `aws s3 rb s3://<bucket-name> --force  --profile personal`
