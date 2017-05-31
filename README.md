ansible disable ipv6
====================
[![Build Status](https://travis-ci.org/ypsman/ansible-ipv6-disable.svg?branch=master)](https://travis-ci.org/ypsman/ansible-ipv6-disable)

Easy way to Disables IPv6 on Debian and Ubuntu Servers! <p>
Dont forget to reboot to avoid Problems!

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.ipv6-disable
