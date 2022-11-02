
git clone https://github.com/qf-devops/ansible-nginx.git

ssh-keygen
id_rsa
id_rsa.pub
copy public content to ~/.ssh/authorized_keys in target node 

ansible-playbook -i inventory site.yml -e "version=2.0.0"

ansible-playbook -i inventory jenkins.yml
