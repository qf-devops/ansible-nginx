ssh-keygen
id_rsa
id_rsa.pub
copy public content to ~/.ssh/authorized_keys in target node 

ansible-playbook -i inventory site.yml
