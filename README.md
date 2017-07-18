# django_official_tutorial

### With vagrant file you will have Ubuntu 14.04 with preinstalled:
 * Python
 * MySQL

### Requirements

 * [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
 * [VirtualBox Oracle VM VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads)
 * [Vagrant](https://www.vagrantup.com/downloads.html)
 * [Vagrant plugins]

### Installation
 
 * Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
 * Install [VirtualBox Oracle VM VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads)
 * Install [Vagrant](https://www.vagrantup.com/downloads.html)
 * vagrant plugin install vagrant-json-config
 * vagrant plugin install vagrant-rsync-back
 * vagrant plugin install vagrant-aws


### Development Workflow
* `git clone` this repository:
```bash
# Clone with HTTPS
$ git clone https://github.com/curious725/django_official_tutorial.git
# Clone with SSH
$ git clone git@github.com:curious725/django_official_tutorial.git
```  

* To start development run
```bash
 $ vagrant up dev
 $ vagrant ssh dev
 $ cd /vagrant
 $ source venv/bin/activate
 $ cd /polls/
 $ python manage.py runserver 0.0.0.0:8000
 ```
 * Navigate to [http://localhost:8000/](http://localhost:8888/) to access server.
 
