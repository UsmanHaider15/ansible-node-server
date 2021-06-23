**NOTE:** AWS ubuntu machine has `ubuntu` user pre configured. This playbook uses that user.

Run playbook using following command.  
`ansible-playbook --private-key=~/aws_keys/aws_pair.pem -i inventory playbook.yml -u ubuntu`
