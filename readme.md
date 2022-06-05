# Web server

## Requirements
```bash
ansible-galaxy install geerlingguy.docker
ansible-galaxy install hispanico.nginx_revproxy
```

## Run
```bash
ansible-playbook playbook.yml -i inventory --ask-vault-pass
```