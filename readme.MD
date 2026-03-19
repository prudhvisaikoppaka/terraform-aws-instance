# AWS EC2 Instance
You can create EC2 instance in company using this module

## Inputs

* ami_id(optional) - AMI ID that need to be used by instance. Default is devops-practice i.e.ami-0220d79f3f480ecf5
* instance_type (Optional) - Instant type to be used by instance. Valid values are t3.micro, t3.small, t3.medium. Default is t3.micro
*sg_ds (Required) - A list of security Group IDs to attach instance
* tags (Required) - A map of tags to be associated with instance

## Outputs
* public_ip - Publuc IP of the instance created.
* private_ip - Private IP of the instance created.
* id - Instance ID of the instnace created.