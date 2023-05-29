# [repository_hashicorp](#repository_hashicorp)

Adds the official hashicorp repository to your system.

|GitHub|GitLab|Quality|Downloads|Version|
|------|------|-------|---------|-------|
|[![github](https://github.com/mullholland/ansible-role-repository_hashicorp/workflows/Ansible%20Molecule/badge.svg)](https://github.com/mullholland/ansible-role-repository_hashicorp/actions)|[![gitlab](https://gitlab.com/opensourceunicorn/ansible-role-repository_hashicorp/badges/master/pipeline.svg)](https://gitlab.com/opensourceunicorn/ansible-role-repository_hashicorp)|[![quality](https://img.shields.io/ansible/quality/57630)](https://galaxy.ansible.com/mullholland/repository_hashicorp)|[![downloads](https://img.shields.io/ansible/role/d/57630)](https://galaxy.ansible.com/mullholland/repository_hashicorp)|[![Version](https://img.shields.io/github/release/mullholland/ansible-role-repository_hashicorp.svg)](https://github.com/mullholland/ansible-role-repository_hashicorp/releases/)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/mullholland/ansible-role-repository_hashicorp/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- name: Converge
  hosts: all
  become: true
  gather_facts: true
  # vars:
  #   example_var: "value"
  roles:
    - role: "mullholland.repository_hashicorp"
```



## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/mullholland/ansible-role-repository_hashicorp/blob/master/requirements.txt).


## [Context](#context)

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://mullholland.net) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/mullholland/ansible-role-repository_hashicorp/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/mullholland):

|container|tags|
|---------|----|
|[EL](https://hub.docker.com/repository/docker/mullholland/docker-centos-systemd/general)|all|
|[Amazon](https://hub.docker.com/repository/docker/mullholland/docker-amazonlinux-systemd/general)|Candidate|
|[Fedora](https://hub.docker.com/repository/docker/mullholland/docker-fedora-systemd/general)|all|
|[Ubuntu](https://hub.docker.com/repository/docker/mullholland/docker-ubuntu-systemd/general)|all|
|[Debian](https://hub.docker.com/repository/docker/mullholland/docker-debian-systemd/general)|all|

The minimum version of Ansible required is 2.10, tests have been done to:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them in [GitHub](https://github.com/mullholland/ansible-role-repository_hashicorp/issues)

## [License](#license)

[MIT](https://github.com/mullholland/ansible-role-repository_hashicorp/blob/master/LICENSE).

## [Author Information](#author-information)

[Mullholland](https://mullholland.net)

Please consider [sponsoring me](https://github.com/sponsors/mullholland).
