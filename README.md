Ansible Role for ec2
=====================

Ansible Role for creating aws ec2 key, instance and add it to route53.

Requirements
------------

This role require Ansible 2.0 or higher.

This role was designed for Red Hat 7.

### pre-reqs option 1: use ami

Create a ~/.boto file:

    [Credentials]
    aws_access_key_id = XXXXXXXXXXXXXXXX
    aws_secret_access_key = YYYYYYYYYYYYYYYYYYYYYYYYYYYY