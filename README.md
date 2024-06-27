# ansible

This is my awesome Ansible repository!

### Ad-hoc commands on ansible

İşlem yapılacak tüm host'ları listeler

`ansible --list-hosts all`

`ansible -m gather_facts all`

`ansible -m apt -a "name=pass state=present update_cache=yes" --become --ask-become-pass`
