# CSYE 6225 Fall '22

## AWS CloudFormation

### Running instructions (replace profile with the profile where you want to create a stack and StackName with desired name of the stack)

aws cloudformation create-stack --stack-name {StackName} --template-body file://csye6225-infra.yaml --capabilities CAPABILITY_NAMED_IAM --profile {profile}