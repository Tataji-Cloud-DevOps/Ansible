# Ansible

### Configuration management tools: The tools that helps in making the  OS level with much more advanced features tools are consider under the configuration management tools.

    1.CF Engine
    2.Puppet
    3.Chef
    4.Ansible

### If we use a CM tool :

1) we dont need to clone the code 
2) we dont need to sign in to the server
3) we dont need to run it manually.
4) if we are having 20 servers we can run at time but in bash we need to login to server and we can also at a time,
   but in bash we need to run 100 server it takes time.

### It is a tool from IBM

# Ansible though it is a open source it has two components
 1) Ansible core 
 2) Ansible

### Ansible solves the shell  problems 
  1) Ansible is declarative (it supports any flavour of linux like redhat,ubuntu)
  2) Ansoble supports the heterogeneous by default.
  3) Ansible can scale to large infrastrcuture.

### Ansible works on both Push and Pull mechanism

Push : If we telling something to the server(main server) and the instructions are pushed to respective node (servers)
Pull : If the infrastructure is so dynamic that means it is scalinmg up and down ( 100 to 200 servers and 200 to 50 servers ) at that time when the server comes up the server is connected to the ansible and download the code locally and this mechanism is called pull.

### why ansible is famous or adopted:
* it is agent less
* Ansible works on ssh

### What we need to do , for ansible to work 
* Ensure ansible is able to communicate with all the infra that needs cm 
* Ensure there are a common set of credentials for the purpose of ansible.

