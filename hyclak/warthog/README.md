# Ansible Collection - hyclak.warthog

This collection includes Ansible roles and content to manage [Warthog Nodes](https://warthog.network/).

Roles included in this collection (click on the link to see the role's README and documentation):

- `hyclak.warthog.warthog_node` ([documentation](https://github.com/hyclak/ansible-warthog/blob/master/roles/warthog_node/README.md))

## Installation

Install via Ansible Galaxy:

```shell
ansible-galaxy collection install hyclak.warthog
```

Or include this collection in your playbook's requirements.yml file:

```yaml
---
collections:
  - name: hyclak.warthog
```

## Usage

Here's an example playbook which installs a Warthog Public Node:

```yaml
---
- name: Prepare Warthog Node
  hosts: warthog
  become: true

  roles:
    - warthog-node
```

See the full documentation for each role in the role's README, linked above.

## License

MIT

## Author

This collection was created by [Matthew Hyclak](hyclak@gmail.com).
