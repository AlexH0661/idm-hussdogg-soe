
## Install role dependencies

```bash
ansible-galaxy install -r requirements.yml
```

## Run role

```bash
ansible-playbook playbook.yaml -Kkv --ask-vault-pass
```
