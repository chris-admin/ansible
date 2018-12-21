# ansible

create keypair


mkidir /root/.ssh
cd /root/.shh

ssh-keygen -t rsa -b 4096

cat id_rsa.pub > authorized_keys


-> id_rsa is the private key (your key to access this server)
