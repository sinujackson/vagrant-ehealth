# Vagrant-ehealth

Vagrant-ehealth is a vagrant script to install two popular open source EMR systems: OpenMRS and OSCAR McMaster. RStudio server is also installed along with these into a ubuntu trusty32 virtual machine.

## How to Use
- Install [VirtualBox for your OS](https://www.virtualbox.org/)
- Install [Vagrant for your OS](https://www.vagrantup.com/)
- Unzip / Clone this repository into a folder [Use the 'Download Zip' on the right panel]
- cd to that folder

```sh
vagrant up
```

> It takes approximately 30 minutes to create the machine initially.

## Access in your browser:
- Access OpenMRS at http://127.0.0.1:8001/openmrs (mysql password: mysql) (login:admin password:Admin123)
- Access OSCAR at http://127.0.0.1:8001/Oscar10_12 (default login password on screen)
- Access R Studio Server at http://127.0.0.1:8002/ (login:vagrant password:vagrant)

## Suspend / Power down / Destroy
To suspend the machine use and resume later
```sh
vagrant suspend
vagrant resume
```
To power down the machine and restart later
```sh
vagrant halt
vagrant up
```
To destroy the machine and recreate
```sh
vagrant destroy --force
vagrant up
```

### Version
1.0.0

### Credits
- [vagrant-OpenMRS](https://github.com/crolfe/vagrant-OpenMRS)
- [OpenMRS](http://openmrs.org/)
- [OSCAR](https://oscar-emr.com/)

### Disclaimer
This is for testing only. Not suitable for production.

### For more information visit [NuChange Blog](http://nuchange.ca) mk

### Contribute
pull-requests welcome



