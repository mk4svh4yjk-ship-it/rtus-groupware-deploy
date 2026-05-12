# rtus-groupware-deploy

Ansible playbooks for the RaccoonTech US groupware (`groupware.us.raccoontechcorp.com`).

Contract work for RaccoonTech US (라쿤테크 미국 법인), the US subsidiary of RaccoonTech.

## Deploy

```bash
ansible-galaxy collection install community.docker
ansible-playbook site.yml                       # prod
ansible-playbook -i dev/staging/hosts.yml site.yml --ask-vault-pass   # staging
```

Staging vault is not in the repo. Ask Divya for the file.
