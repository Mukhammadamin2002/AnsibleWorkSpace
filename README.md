### Ansible Work Space

#### Running ping command to two other server 
`ansible {hostname} -m ping`
#### View result in the link below 
[view image](https://exadel.s3.eu-central-1.amazonaws.com/ansible.jpg)

#### Running ansible playbook 
`ansible-playbook {filename.yaml}`

#### Running specific shell command on specific hosts
`ansible {hostname} -m shell -a "command here"`

#### Visit below link to see Wordpress Project running in Docker Container
[wordpress project](https://exadel.s3.eu-central-1.amazonaws.com/ansible_wordpress.jpg)

#### See Two Running Containers in below link | Wordpress & MariaDB containers are running
[container list](https://exadel.s3.eu-central-1.amazonaws.com/ansible_container.jpg)

#### Ansible Dynamic Inventory
`aws_ec2` plugin is used to get ip of ec2 instance dynamically 

#### As our Ansible Server part of Instance in AWS I have Provided I AM role to that server it wont need to provide secret_key and access_id in `aws_ec2.yaml` file