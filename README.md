Usage:

Start:
ansible-playbook VCenter_Operations.yml --tag "start" --extra-vars "guest=Sonarr" --ask-vault-pass

Stop:
ansible-playbook VCenter_Operations.yml --tag "stop" --extra-vars "guest=Sonarr" --ask-vault-pass

Restart:
ansible-playbook VCenter_Operations.yml --tag "restart" --extra-vars "guest=Sonarr" --ask-vault-pass

List:
ansible-playbook VCenter_Operations.yml --tag "list" --extra-vars "guest=Sonarr" --ask-vault-pass

