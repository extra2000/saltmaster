# saltmaster-box

| License | Versioning | Build |
| ------- | ---------- | ----- |
| [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) | [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release) | [![Build Status](https://travis-ci.com/extra2000/saltmaster-box.svg?branch=master)](https://travis-ci.com/extra2000/saltmaster-box) [![Build status](https://ci.appveyor.com/api/projects/status/bn5yuhh0osbu863r/branch/master?svg=true)](https://ci.appveyor.com/project/nikAizuddin/saltmaster-box/branch/master) |

Automate SaltStack Master deployment.


## Getting Started

Choose Vagrant file from `vagrant/examples/`. For example:
```
$ cp -v vagrant/examples/Vagrantfile.saltmaster-box.centos-7.x86_64.example vagrant/Vagrantfile.saltmaster-box
```

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
