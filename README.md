# codingcats-rails-server

This is a virtual machine we use to test an actual production deployment.

# Requirements

To run this VM, you need [Vagrant](https://www.vagrantup.com/downloads.html).

# What it does

Vagrant enables to have a reproducible work environment.
In the terminal, run `vagrant up` in the directory, where the `Vagrantfile` is.
This boots an Ubuntu 14.04x64 Linux. On the first time it takes a moment, because it needs to download
the VM image.

When it finished booting, you can access the VM via `vagrant ssh`.


In case you messed up and want to restart from scratch, run `vagrant destroy`. This destroys the VM and you
can start from a clean state again.
