![Cloud formation background](https://d1.awsstatic.com/photoheaders/Photo-Header_CloudFormation.901670122179f23c00953e3c71de055cbd5308ad.png)

### About this project

This project deploys the cloud infraestructure and a basic website on AWS, using AWS Cloud Formation

### Prerequisites

- You need to create an account in AWS

#### Required libraries
- aws-cli/1.16.166 - [Installation instructions](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
- Python/2.7.15

### Quick Usage

- You need to modify the template in network.yml to have your account settings

#### 1. Install

- aws-cli/1.16.166 - [Installation instructions](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
- Python/2.7.15

#### 2. Create the infrastructure and deploy the website

Run this in your terminal 

```
$ ./create.sh deployhighpinzon network.yml network-parameters.json
```

#### 3. Update the infrastructure and deploy the website

Run this in your terminal

```
$ ./update.sh deployhighpinzon network.yml network-parameters.json
```

#### 4. Open the website

To open the website you need the URL of the Load Balancer

http://elasticloadbalancer-2059187917.us-east-2.elb.amazonaws.com/

[Link to the website](http://elasticloadbalancer-2059187917.us-east-2.elb.amazonaws.com/)