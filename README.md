# ansible-k8s-dev

Playbook to install libs needed for k8s development. This includes:

- zsh
  - oh-my-zsh
- protoc
- docker
- zeromq
- Golang
  - controller-gen
  - mock-gen
  - kind
  - protoc-gen-go
- kubectl
- kubebuilder
- k9s
- terraform
- awscli

## Prerequisites

- Python
- Ansible 2.8+

## Quickstart

```bash
ansible-galaxy install -r requirements.yml
ansible-playbook dev-install.yml -u $USER --ask-become-pass
```
