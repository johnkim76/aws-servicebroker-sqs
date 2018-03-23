# Amazon SQS for the AWS Service Broker Demo
A Demo [Amazon SQS](https://aws.amazon.com/sqs/) [APB](https://github.com/ansibleplaybookbundle/ansible-playbook-bundle) to show various error situations

## Prerequisites

**IAM resources** - see the [AWS Service Broker Requirements](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/Overview.md#requirements) for details

## Plans
### Error - Region
This plan will fail due to an invalid region value with default parameters

### Error - MaximumMessageSize
This plan will fail due to an invalid max msg size value with default parameters


## Retained resources

No resources are retained. The SQS queue, data and all associated resources will be fully removed if the Service Instance is deleted.

## Resources

[Getting Started With OCP and the AWS Service Broker](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/getting-started.md)
[AWS Service Broker Overview](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/Overview.md)
[FAQ](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/FAQ.md)
[Troubleshooting](https://github.com/awslabs/aws-servicebroker-documentation/blob/master/Troubleshooting.md)

## License

This library is licensed under the Apache 2.0 License.
