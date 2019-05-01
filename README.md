<p align="center"><img src="https://i.imgur.com/mFCIQBj.png" /></p>

> Ansible role to setup Amazon EFS 

## Role Variables

```yamlex
efs_mount_id: ""
efs_mount_point: ""
```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - role: ansible-role-mount_efs
      become: true
```
## 👬 Contribution
- Open pull request with improvements
- Discuss ideas in issues
- Reach out with any feedback [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/anmol_nagpal.svg?style=social&label=Follow%20%40anmol_nagpal)](https://twitter.com/anmol_nagpal)
