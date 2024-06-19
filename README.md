# ansible

This is my awesome Ansible repository!

### Ad-hoc commands on ansible

`ansible --list-hosts all`

`ansible -m gather_facts all`

`ansible -m apt -a "name=pass state=present update_cache=yes" --become --ask-become-pass`
