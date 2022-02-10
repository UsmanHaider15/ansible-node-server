**NOTE:** AWS ubuntu machine has `ubuntu` user pre configured. This playbook uses that user.

Install community.general so that we could install pm2
`ansible-galaxy collection install community.general`

Run playbook using following command.  
`ansible-playbook --private-key=~/aws_keys/aws_key.pem -i inventory playbook.yml -u ubuntu`
