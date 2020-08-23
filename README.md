# saltmaster

Automate SaltStack Master deployment.


## Getting Started

Generate Saltstack master key for `saltmaster-box`:
```
$ cd salt/keys
$ openssl genrsa -out saltmaster-box.pem
$ openssl rsa -in saltmaster-box.pem -pubout -out saltmaster-box.pub
```

Create Vagrant box `saltmaster-box` and then ready for localhost deployment:
```
$ vagrant up --provider=libvirt
```
