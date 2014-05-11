ansible-rails
==============

Install a single instance of nginx, passenger, and mongodb

####Dependencies 

```
ansible-galaxy install abtris.nginx-passenger
```


####Optional

Change ```- hosts: all``` to a more specific group or IP


####Execute

```
ansible-playbook nginx-passenger-mongo.yml
```


####Future

Setup auth for mongo
Deploy rails app by specifying git repo