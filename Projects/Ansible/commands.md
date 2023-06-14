test inventory is reachable
```shell
ansible all -m ping
```



run playbook & input sudo password 
```shell
ansible-playbook addsshkey.yml --ask-become-pass
```