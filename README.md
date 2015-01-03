Ansible Monit
==============

Install and configure monit on Debian server.

Installation
------------

git submodule add git@github.com/boostmyshoporganization/ansible-monit roles/monit

```yaml
roles:
    - monit
```

Configuration
-------------

```yaml
monit:
  email: contact@example.com
  user: admin
  password: my_password
```