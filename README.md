hedgedoc
=================

Setup HedgeDoc(work in progress)

OS Platform
-----------------

### Debian

- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

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
