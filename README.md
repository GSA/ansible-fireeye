ansible-fireeye
=========

Endpoint Security enables detection and response using knowledge learned on the front line of incident response and managing our customers defense. This ansible role installs and configures the agent required to communicate with client machines.

Requirements
------------

```bash
redhat_fireeye_agent_filename: #redhat installer msi
windows_fireeye_agent_filename: #windows installer msi
```

Role Variables
--------------

```bash
None
```

Dependencies
------------
Acquire Installers
```bash
fireeye.rpm - redhat installer package
fireeye.msi - windows installer package
```

Example Playbook
----------------

```bash
    - hosts: servers
      roles:
         - ansible-fireeye
```

License
-------

MIT

Author Information
------------------

Lance White - GSA/GEO
