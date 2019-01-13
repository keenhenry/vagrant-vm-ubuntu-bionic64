# vagrant-vm-ubuntu-bionic64

A Vagrant project for setting up Python Hahow development environment

## General Vagrant and VirtualBox Setup Information ###

### Setting up `vagrant` autocompletion ###

On my machine, here is what I did:

```bash
$ sudo cp /opt/vagrant/embedded/gems/2.2.3/gems/vagrant-2.2.3/contrib/bash/completion.sh /etc/bash_completion.d/vagrant.sh
$ . /etc/bash_completion
```

See [reference][1] for more details.

### Vagrant Version For This Project ###

```bash
$ vagrant version
Installed Version: 2.2.3
Latest Version: 2.2.3

You're running an up-to-date version of Vagrant!
```

### VirtualBox Version For This Project ###

```bash
$ virtualbox --help
Oracle VM VirtualBox Manager 5.2.22
(C) 2005-2018 Oracle Corporation
All rights reserved.

...
```

### Vagrant Box Information ###

```bash
# Start guest VM
$ vagrant up

# Connect to guest VM
$ vagrant ssh

# Inside guest VM, show guest OS information
$ uname -a
Linux ubuntu-bionic 4.15.0-43-generic #46-Ubuntu SMP Thu Dec 6 14:45:28 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
```

[1]: https://debian-administration.org/article/316/An_introduction_to_bash_completion_part_1
