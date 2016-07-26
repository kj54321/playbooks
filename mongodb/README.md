# Ansible for MongoDB
Single node Mongodb on RHEL 7

Contains both playbook and role version.

07/26 Updated config file to support version 3.X and fixed systemd start failure issue.

## Installation
- Feel free to fork or clone this repository

- In your playbook:

```yaml
roles:
  - mongodb
```

## Usage

```yaml
vars:

  mongodb:
    dbpath: /var/lib/mongo
````
