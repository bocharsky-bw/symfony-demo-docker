# Dockerized Symfony Demo application

This repository provides a template to spin [Symfony Demo][1] application
on `Docker`'s [Nginx][2] + [PHP-FPM][3] + [MySQL][4] linked image containers
that are provisioning with [docker-compose][5] tool.

## Mac OS X

If you are on `Mac OS X` - you should used any Linux-based virtual machine (VM)
for `Docker` host. Take a look at the [Boot2Docker][6] lightweight Linux distribution
which made specifically to run `Docker` containers. If you prefer to use [Vagrant][8]
for building and distributing development environments via VM - look closely
to the [CoreOS Vagrant][7] image.


[1]: https://github.com/symfony/symfony-demo
[2]: https://hub.docker.com/_/nginx/
[3]: https://hub.docker.com/_/php/
[4]: https://hub.docker.com/_/mysql/
[5]: https://github.com/docker/compose
[6]: https://github.com/boot2docker/boot2docker
[7]: https://github.com/coreos/coreos-vagrant
[8]: https://github.com/mitchellh/vagrant
