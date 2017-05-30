Playbooks
=========

Install Ansible
---------------

```bash
brew install ansible
```

Run
---

### workstation
```bash
cp group_vars/workstation.example group_vars/workstation
# fill your preferences in group_vars/workstation
ansible-playbook workstation.yml --ask-become-pass
```
