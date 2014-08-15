Setup (Ubuntu 14.04)
===================
1. `sudo apt-get install ruby ansible`
1. `gem install librarian-ansible`
1. `librarian-ansible install`
1. `ansible-playbook -i localhost.inventory -K playbook.yml`
