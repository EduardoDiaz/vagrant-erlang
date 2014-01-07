Vagrant-erlang-kerl
===================

It is a script to build a linux environment (precise64) development for erlang
in [vagrant][1] with [kerl][2] and [rebar][3] installed and create boxes.


Quickstart
----------

install [vagrant][1]

Download the required vagrant box

    vagrant init precise64 http://files.vagrantup.com/precise64.box

Start vagrant
    
    vagrant up
    vagrant ssh


   [1]: https://github.com/mitchellh/vagrant "Vagrant - Tool for building and distributing virtualized development environments"
   [2]: https://github.com/spawngrid/kerl "Kerl - Easy building and installing of Erlang/OTP instances"
   [3]: https://github.com/basho/rebar "Rebar - "
