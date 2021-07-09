## Wordpress Installation with Ansible

### Prerequisites

#### Packages Requirements
```
Wordpress Version: 5.7.2
PHP Version: 7.4 or greater
Mysql Version: 5.6 or greater
MariaDB Version: 10.1 or greater
Apache/2.4.37 (centos)
```
#### Server Requirements
Webserver
```
Operating System: CentOS 8
CPU/RAM: 1 / 1GB
Storage: 10 GB or more
```

Database Server
```
Operating System: Ubuntu 20.04
CPU/RAM: 1 / 1GB
Storage: 10 GB or more
```


### Diagram

### Directory Structure
```
.
├── dev_inventory.yaml
├── playbooks
│   ├── add_ansible_user.yaml
│   ├── database.yaml
│   ├── packages.yaml
│   ├── ping.yaml
│   └── webserver.yaml
├── README.md
└── variables
    ├── database_vars.yaml
    ├── ping_vars.yaml
    └── webserver_vars.yaml
```

### Packages
#### Webserver: 
```
PHP 7.2.24
Apache/2.4.37 (centos)
mysql  Ver 8.0.21
```