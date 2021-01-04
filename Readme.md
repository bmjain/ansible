### Execution Command

clone this repo

cd playbooks
ansible-playbook --connection=local --inventory 127.0.0.1, -i /etc/ansible/hosts --limit 127.0.0.1 user_create.yml
