# Ansible role for dovecot and postfix


Setup dovecot and postfix.

## Requirements

- Debian
- Ubuntu

## Role Variables

see defaults/main.yml

## Dependencies

None.

## Example Playbook

Example:

    - hosts: all
      become: yes
      roles:
      - role: znz.dovecot-postfix

## License

MIT License
