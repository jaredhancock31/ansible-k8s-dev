# ansible-k8s-dev

Playbook to install libs needed for k8s development

## Prerequisites
- Python
- Ansible 2.8+

## Quickstart

```bash
ansible-galaxy install -r requirements.yml
ansible-playbook dev-install.yml
```

### TODOs
- be flexible with bash/zsh
- repair shell after completion for root-sensitive roles
- awscli
- java
- docker
- zsh
