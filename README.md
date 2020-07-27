### install_tomcat
install tomcat

### How to use anible-mothership(https://github.com/Bharathkumarraju/ansible-mothership) roles

```
1. git submodule init

2. git submodule add git@github.com:Bharathkumarraju/ansible-mothership.git
once you added like  above it creates .gitmodules file.
and ansible-mothership in current directory thats it all done.

3. In ansible.cfg update the rolepath as roles:ansible-mothership/roles

```

### How to be upto-dated with gitsubmodule repos run  below commands (or) make it a script

```

   1. cd $(git rev-parse --show-toplevel)
   2. git pull --quiet --rebase
   3. git submodule sync && git submodule update --init

```
