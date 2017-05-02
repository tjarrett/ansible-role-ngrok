# Ansible Role: Ngrok

Installs [Ngrok](https://ngrok.com), on RHEL/CentOS or Debian/Ubuntu servers.

## Requirements

No special requirements; note that this role requires root access, so either
run it in a playbook with a global `become: yes`, or invoke the role in your
playbook like:

```yml
- hosts: all
  roles:
    - role: phalcon.ngrok
      become: yes
```

## License

This project is open-sourced software licensed under the MIT License. See the LICENSE file for more information.
