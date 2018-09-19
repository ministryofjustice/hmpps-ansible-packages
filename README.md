hmpps-ansible-packages
=========

Base package mananger for installing some stuff


Role Variables
--------------

```yaml
install_jdk: boolean #default false
# If we're installing java then the below can be set
java_home: path #default /etc/java
java_version: string #default

system_installer:  
   packages:
    - list
    - of 
    - packages
    - to 
    - install

```
Dependencies
------------

None

License
-------

MIT
