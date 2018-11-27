# ansible_config_conditionals

We should desire automation, my files achieve this. We use the ```when``` command to select the specific package manager we want to download. It functions much the same as an ```if``` statement.

The CentOS_tasks.yml file will install nexus on to a CentOS machine whose package manager is ```yum```, and the Ubuntu_tasks.yml will install jenkins on an Ubuntu machine whose package manager is ```apt```. It is the package manager that we are primarily concerned with.

*NOTE:*
We must specifically install openjdk_8_jdk on the Ubuntu machine. Remember, jenkins will only run on version 8 of Java.
