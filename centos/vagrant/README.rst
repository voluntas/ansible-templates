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


