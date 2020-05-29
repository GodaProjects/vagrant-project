# Vagrant project
A project for playing around with vagrant
https://www.vagrantup.com/

## Using clt
Create container
```
vagrant init ubuntu/trusty64
vagrant up
```

the Vagrantfile gets created automaticaly.

For SSH in to server
```
vagrant ssh
vagrant ssh goda_host_1
```

To check memory
```
free -m
```

To stop or destroy the server.
```
vagrant suspend
vagrant halt
vagrant destroy
```

Resuming from vagrant suspend command.
```
vagrant resume
```

## With docker
While i understand how to get docker provider working with Vagrant, i get the below error and i dont have time or patience to solve this. Also I might never use this. So much for vagrant.
```
OCI runtime create failed: container_linux.go:348: starting container process caused "process_linux.go:301: running exec setns process for init caused \"exit status 23\"": unknown
```