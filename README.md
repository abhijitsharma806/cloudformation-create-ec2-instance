# cloudformation-create-ec2-instance
Create EC2 Instance by using CloudFormation templates

  * To run this cloudformation template you can use via GUI/CLI.
  * To run this via CLI you need to install AWS CLI.
  * Follow the below links to install the AWS CLI.
  
## Installing the AWS CLI
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html


## Install the AWS CLI on Linux
https://docs.aws.amazon.com/cli/latest/userguide/install-linux.html


## Install the AWS CLI on Windows
https://docs.aws.amazon.com/cli/latest/userguide/install-windows.html


## Install the AWS CLI on macOS
https://docs.aws.amazon.com/cli/latest/userguide/install-macos.html


## Install the AWS CLI in a Virtual Environment
https://docs.aws.amazon.com/cli/latest/userguide/install-virtualenv.html


## Install the AWS CLI Using the Bundled Installer (Linux, macOS, or Unix)
https://docs.aws.amazon.com/cli/latest/userguide/install-bundle.html

## Configure the AWS CLI
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html

## Validate CloudFormation Json Templates
```
aws cloudformation validate-template --template-body file://create_ec2_instance.json
```

## Create Stack In CloudFormation
  * The region you have configured in the AWS CLI, It will create the S3 bucket in the same region.
```
aws cloudformation create-stack --stack-name EC2Instance --template-body file://create_ec2_instance.json
```

## Delete Stack
```
aws cloudformation delete-stack --stack-name EC2Instance
```
## Thanks
