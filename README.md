# ansible

create keypair


mkidir /root/.ssh
cd /root/.shh

ssh-keygen -t rsa -b 4096

cat id_rsa.pub > authorized_keys


-> id_rsa is the private key (your key to access this server)


# Basics

Run script on localhost:
ansible all -i localhost, -m shell -a '/bin/echo hello word'

Run a playbook:
ansible-playbook -i localhost, setup_http.yaml
