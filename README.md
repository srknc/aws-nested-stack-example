
## Description
AWS CloudFormation nested stack example

## Usage
- Upload all `.yaml` files to a bucket
- Change the bucket names at `root.yaml` file
aws cloudformation create-stack --stack-name test  --template-url https://s3.amazonaws.com/cloudformation-1548978758/root.yaml --parameters  ParameterKey=resourceName1,ParameterValue=name1 ParameterKey=resourceName2,ParameterValue=name2
