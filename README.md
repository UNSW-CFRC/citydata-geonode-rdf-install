# geonode_ext_install
Ansible playbook to install Geonode semantic extensions by [rob-metalinkage](https://github.com/rob-metalinkage):
* [django-rdf-io](https://github.com/rob-metalinkage/django-rdf-io)
* [django-skosxl](https://github.com/rob-metalinkage/django-skosxl)
* [django-gazetteer](https://github.com/rob-metalinkage/django-gazetteer)
* [uriredirect](https://github.com/rob-metalinkage/uriredirect)

## Requirements
* Ubuntu 16.04
* Geonode 2.4 - e.g. installed with [geonode_install playbook](https://github.com/UNSW-CFRC/geonode_install)
* Ansible on your controlling machine - [installation instructions](http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-apt-ubuntu)

## Usage
Run the playbook from your controlling machine:
> ansible-playbook geonode_rdf_install.yml --extra-vars "host=HOST_NAME"
