# ansible
ansible



admin1@ansible:~/Desktop/ansible$ ansible-playbook -i inventory clone_code_linux2.yml 



admin1@ansible:~/Desktop/ansible$ ansible-playbook create_user.yml -i inventory --extra-vars "created_username=testuser"
