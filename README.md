hmpps-ansible-packages
=========

Base package mananger for installing some stuff


Role Variables
--------------

```yaml
install_jdk: true
# If we're installing java then the below can be set
java_home: /usr/java
java_version: 8u181

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
