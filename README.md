freehck.helm
=========

install helm

Role Variables
--------------

`helm_version`: version of helm to install

Example
-------

    - hosts: k8s_master
      become: true
      roles:
        - role: freehck.helm

Install
-------

This role can be installed from [Ansible Galaxy](https://galaxy.ansible.com/):

`ansible-galaxy install freehck.helm`

License
-------

MIT

Author Information
------------------

Alex Chistyakov, <alexclear@gmail.com>
Dmitrii Kashin, <freehck@freehck.ru>
