[![Docker Stars](https://img.shields.io/docker/pulls/mlabouardy/komiser.svg)](https://hub.docker.com/r/mlabouardy/komiser/) 
[![CocoaPods](https://img.shields.io/cocoapods/l/AFNetworking.svg)](https://github.com/mlabouardy/komiser/LICENSE) [![CircleCI](https://circleci.com/gh/mlabouardy/komiser/tree/master.svg?style=svg&circle-token=d35b1c7447995e60909b24fd316fef0988e76bc8)](https://circleci.com/gh/mlabouardy/komiser/tree/master) [![Go Report Card](https://goreportcard.com/badge/github.com/mlabouardy/komiser)](https://goreportcard.com/report/github.com/mlabouardy/komiser) [![Docker Stars](https://img.shields.io/github/issues/mlabouardy/komiser.svg)](https://github.com/mlabouardy/komiser/issues)  



## Download

Below are the available downloads for the latest version of Komiser (1.0.0). Please download the proper package for your operating system and architecture.

### Linux:

```
wget https://s3.us-east-1.amazonaws.com/komiser/1.0.0/linux/komiser
```

### Windows:

```
wget https://s3.us-east-1.amazonaws.com/komiser/1.0.0/windows/komiser
```

### Mac OS X:

```
wget https://s3.us-east-1.amazonaws.com/komiser/1.0.0/osx/komiser
```

## Docker

Use the official Komiser image:

```
docker run -d -p 3000:3000 -v credentials:/root/.aws/credentials --name komiser mlabouardy/komiser:1.0.0
```

Credentials are installed on your container into the *~/.aws/config* and *~/.aws/credentials* properties files. You can override the default environment variables: **PORT**, **DURATION**.

## Supported AWS Services

* EC2
* EBS
* Snapshots
* Security Groups
* Access Control Lists
* Autoscalling groups
* ELB
* VPC
* Key Pairs
* Nat Gateway
* Internet Gateway
* Elastic IP
* Route Table
* Billing
* Lambda Functions
* RDS
* DynamoDB
* S3
* Route53
* SQS
* SNS
* IAM
* CloudWatch Alarms
* CloudFront Distributions

## TO DO

* EMR
* ECS
* Kinesis
* Elastic Beanstalk
* Glacier

## Maintainers

* Mohamed Labouardy

## License

MIT
