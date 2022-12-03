hedgedoc
=================

Setup hedgedoc

OS Platform
-----------------

### Debian

- bullseye

Role Variables
--------------

### `hedgedoc_version`

HedgeDocのバージョン/ブランチ

### `hedgedoc_cfg`

HedgeDocの設定

Dependencies
--------------

- nodejs
Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: hedgedoc
```

License
--------------

Apache License 2.0
