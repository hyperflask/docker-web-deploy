# Docker Web Deploy

**⚠️ This is a work in progress project which is not functionnal yet**

Deploy container based web apps in seconds to baremetal, cloud VMs or various cloud container hosting platforms.

Available targets:

 - Any server from any provider (bare metal / VM) using [Ansible](https://ansible.com) and [Uncloud](https://github.com/psviderski/uncloud)
 - [Fly.io](https://fly.io)

When hosting the app yourself, the infrastructure is kept as simple and straighforward as possible with minimal operations needed. It is meant to deploy apps on a single server. This stack can be run on cheap machines or VMs from any server/cloud providers.

## Usage

Deploy any Dockerfile project:

    $ pip install docker-web-deploy
    $ touch Dockerfile # create your Dockerfile
    $ docker-web-deploy .