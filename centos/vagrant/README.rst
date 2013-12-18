##############
Vagrant
##############

テスト用

box は packer で作る

::

    $ git clone https://github.com/shiguredo/packer-templates
    $ cd packer-templates
    $ cd centos-6.5
    $ packer build -only virtualbox template.json


::

    $ vagrant box add centos-6-5-x64 /path/to/centos-6-5-x64-virtualbox.box
