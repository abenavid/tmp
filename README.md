ssh-keygen -t rsa -b 4096
cat ~/.ssh/id_rsa
paste private key into a machine credential in AAP
Add vars to inventory variables in AAP
    ansible_ssh_common_args: '-o StrictHostKeyChecking=no'
    ansible_user: 'ec2-user'
cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys

Curl example OSI app 
    - wget https://nodejs.org/dist/v6.9.2/node-v6.9.2-linux-x64.tar.gz
