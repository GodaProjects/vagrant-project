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