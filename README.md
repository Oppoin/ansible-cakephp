

This role installs and configures a Debian-backed machine to be used for 
[CakePHP3](http://book.cakephp.org/3.0/en/index.html/), a
PHP web framework. It will be installed behind
`nginx` server with MySQL as a database backend.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install simkimsia.cakephp3

### Documentation

More information about `simkimsia.etherpad` can be found in the docs (Coming soon..)

### Role dependencies

- `debops.etc_services`
- `debops.secret`
- `debops.mysql`
- `debops.nginx`
- `debops.php5`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`CakePHP3` role was written by:
- KimSia Sim | [e-mail](mailto:kimcity@gmail.com) | [Twitter](https://twitter.com/KimStacks) | [GitHub](https://github.com/simkimsia)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role aims to be part of the [DebOps](http://debops.org/) project. README is typed up manually.

