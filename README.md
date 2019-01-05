# Ansible Role: system-watch

Installs system-watch monitoring on Debian and Ubuntu servers.

## Dependencies

  no dependencies

## Example Playbook

    - hosts: localhost
      vars:
        system_watch_repo: ssh://git@git.yourserver.com/log.git
        system_watch_git_status_repos:
          - name: project1
            path: /srv/project1
          - name: project2
            path: /srv/project2
      roles:
        - AlphaNodes.sytem-watch

## License

GPL Version 3

## Author Information

This role was created in 2017 by [AlphaNodes](https://alphanodes.com/).
