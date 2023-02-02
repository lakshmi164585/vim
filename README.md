Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

```
```
# first we have to install nodejs manually on ubuntu and centos7
```
##Manual commands on ubuntu@
```
```
    1 sudo apt update
    2 sudo apt install nodejs
    3 node -v
    4 history 
 ```
## Manual commands on centos7
*   1  sudo yum update
    2  sudo yum install nodejs
    3  curl –sL https://rpm.nodesource.com/setup_10.x | sudo bash -
    4  sudo yum install –y nodejs
    5  node –version
    6  history
```
```
* Creating individual roles for nodejs on both ubuntu and centos7
* Here are we are using when condition for executing in specific nodes 
```
Pulling that roles into local machine by using sftp and calling that roles from main.yaml
```
```
Now we are pushing that roles into github repository
```


    

