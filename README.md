hedgedoc
=================

Setup HedgeDoc

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `hedgedoc_version`

HedgeDocのバージョン

#### `hedgedoc_cfg`

HedgeDocの設定  
@see https://docs.hedgedoc.org/configuration/

#### `hedgedoc_envs`

HedgeDocの環境変数  
@see https://docs.hedgedoc.org/configuration/

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `hedgedoc_root`

#### `hedgedoc_user`

#### `hedgedoc_group`

#### `hedgedoc_repo`

#### `hedgedoc_mode`

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
