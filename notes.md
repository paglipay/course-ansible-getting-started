ansible-playbook -i ansible/hosts nfs-server.yml --private-key=~/.ssh/id_rsa -u ubuntu --extra-vars "ansible_sudo_pass=P@ssw0rd1234"

ansible-playbook -i ansible/hosts main.yml --private-key=~/.ssh/id_rsa -u ubuntu --extra-vars "ansible_sudo_pass=P@ssw0rd1234"