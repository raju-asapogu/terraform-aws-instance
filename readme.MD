# AWS EC2 Instance

This module creates an EC2 instance.

### Inputs

* ami_id - (Optional) Defaults to ````ami-0220d79f3f480ecf5```` bacz we have supplied default value. 
* instance_type - (Required) User must supply instance type either t2.micro, t2.small, t2.medium etc.
* sg_ids - (Required) User must supply a list of security group IDs to attach EC2 Instance.
* tags - (Optional) User can supply tags to be attached to the EC2 instance.


### Outputs

* public_ip - Public IP of the EC2 instance.
* private_ip - Private IP of the EC2 instance.
* instance_id - ID of the EC2 instance.