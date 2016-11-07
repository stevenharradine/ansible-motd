# ansible-motd

This package makes the /etc/motd (Message of the Day) more dynamic.

# Tunables

* ```template_src```(string) - The source location of the motd template
* ```template_dest```(string) - The destination for the motd template
* ```company_name```(string) - The company name that will show up in the motd default template

# Example Playbook

```
- hosts: servers
  roles:
     - role: telusdigital.motd
```

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* Alex Podobnik | [e-mail](mailto:alexandar.podobnik@gmail.com)
