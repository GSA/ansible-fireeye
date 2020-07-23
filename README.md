fireeye [![circleci](https://circleci.com/gh/GSA/ansible-fireeye.svg?style=svg)](https://circleci.com/gh/GSA/ansible-fireeye)
=========

This ansible role installs and configures the fireeye agent required to communicate with client machines.

Requirements
------------

Required Packages (this role requires access to the following packages/installers)
- fireeye.rpm - redhat installer package
- fireeye.msi - windows installer package

Role Variables
--------------

| Variable | Default | Purpose |
| ------ | ------ | ------ |
| redhat_fireeye_agent_filename | "" | redhat installer msi |
| windows_fireeye_agent_filename | "" | windows installer msi |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - fireeye
```

Public domain
-------------

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
