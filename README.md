hedgedoc
=================

Setup HedgeDoc(work in progress)

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `hedgedoc_version`

HedgeDocのバージョン

### `hedgedoc_cfg`

HedgeDocの設定

Dependencies
--------------

- [nodejs](https://github.com/wate/ansible-role-nodejs)

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
