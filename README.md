# ansible-role-exim4
Ansbile role to install and configure Exim4 on Debian based system.

## Prerequisites

None.

## Example Playbook

    - hosts: servers
      roles:
      - role: ansible-role-exim4

## Role variables

The following variables are used for the content of the /etc/exim4/update-exim4.conf.conf file:

    exim4_dc_eximconfig_configtype: local
    exim4_dc_other_hostnames: localhost
    exim4_dc_local_interfaces: '127.0.0.1 ; ::1'
    exim4_dc_readhost: ''
    exim4_dc_relay_domains: ''
    exim4_dc_minimaldns: 'false'
    exim4_dc_relay_nets: ''
    exim4_dc_smarthost: ''
    exim4_CFILEMODE: '644'
    exim4_dc_use_split_config: 'false'
    exim4_dc_hide_mailname: ''
    exim4_dc_mailname_in_oh: 'true'
    exim4_dc_localdelivery: 'mail_spool'


## License

MIT

## Author Information

This role was created in 2018 by Olivier Locard on the behalf of Deveryware.
