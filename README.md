# ansible_playbook_template_django
Ansible playbook template for django deployment

## Sample Command to run playbook
`ansible-playbook -i hosts stage.yml --extra-vars '{"branch": "master", "app_list": ['--all']}' --ask-vault-pass`
