Ansible Role: ara - Moved to https://github.com/openstack/ansible-role-ara.git
=========
Ansible role to install, configure ara on RHEL, Fedora, Centos, Debian and Ubuntu

systemd is configured to start ara on boot, failures

By default embedded server is used to host ara on localhost, if you prefer mod_wsgi then you can set the mod_wsgi variable in defaults/main.yml

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: chaitanyaenr.ara

License
-------

Apache-2.0

Author Information
------------------

Naga Ravi Chaitanya Elluri - nelluri@redhat.com

Copyright
------------------

Copyright 2016 Red Hat, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
