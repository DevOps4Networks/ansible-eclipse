## DevOps4Networks Ansible Eclipse Role

This Ansible Eclipse role is based on the work from [Alban Andrieu](fr.linkedin.com/in/nabla/) which one
may find [here](https://github.com/AlbanAndrieu/ansible-eclipse). It has been extensively rewritten to support:

 - RedHat and Ubuntu
 - Java 8
 - To install plugins by copying to the eclipse/plugins dir
 - To distinguish between the install and dev users

The purpose of the role is to install Eclipse and a variety of plugins, as configured in the 
[defaults](defaults/main.yml.)

This role is tested for use in the OpenDaylight Dev VM, but should be usable in other contexts also.

### Installation

This role requires at least Ansible `v1.6.3`. 

To install it, run:

 TBD

### Role variables

List of default variables available in the inventory:

```yaml
    TBD
```

### Authors and license
 
 [Nathan Sowatskey]()

- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-eclipse/issues)!
