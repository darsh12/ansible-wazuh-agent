wazuh_agent
=========

Ansible role to install and configure wazuh agent


Role Variables
--------------

```yaml
- wazuh_manager_ip: 127.0.0.1
- wazuh_agent_group: linux
- wazuh_manager_password: registration_password
- enable_wazuh_remote_command: True/False
```


Example Playbook
----------------

```yaml
- host: all
  roles:
    - role: darsh12.wazuh_agent
  vars:
    wazuh_manager_ip: localhost
    wazuh_agent_group: linux
    wazuh_manager_password: registration_password
    enable_wazuh_remote_command: False
```

License
-------

BSD

Author Information
------------------

darsh12
