ansible-galaxy install -r requirements.yaml

ansible-playbook main.yml --ask-become --ask-vault-password
