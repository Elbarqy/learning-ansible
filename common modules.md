### packages
- install OS packages
    package: name= state=
- yum #package repository
- apt #package repository
- pip #python packages
- gem #rubygems

=================

### configuration
- copy
- template copy based on a variable
=================

### File Module
- file #create/delete files/dir
- lineinfile ## update a line in a file
- unarchive #extract tar, zip
=================

### System modules
- service
- cron
- user
- seboolean


========================

dependencies can be listed under meta folder in a role