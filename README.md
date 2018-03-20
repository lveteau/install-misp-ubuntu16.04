# install-misp-ubuntu16.04
Installation script for MISP under Ubuntu 16.04

Simple adaptation of [this(misp-vagrant)](https://github.com/MISP/misp-vagrant) for a blank Ubuntu 16.04 server. 

## Development environment for MISP

For a deployment of MISP more ready for a production environment you can use
[this packer script](https://github.com/MISP/misp-packer).

## Deployment of MISP

MISP will be automatically deployed in Ubuntu 16.04

    $ git clone https://github.com/lveteau/install-misp-ubuntu16.04.git /tmp/MISP
    $ cd /tmp/MISP/
    $ sh install.sh

Once the script has finished, MISP is running and listening on your localhost (127.0.0.1).

You can now edit the source code with your favorite editor and test it in your
browser. The only thing is to not forget to restart Apache after a
modification.

Modules activated by default:

* [MISP galaxy](https://github.com/MISP/misp-galaxy)
* [MISP taxonomies](https://github.com/MISP/misp-taxonomies)
* [MISP modules](https://github.com/MISP/misp-modules)


