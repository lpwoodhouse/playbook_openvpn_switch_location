# Ansible Role: switch-location

### <sub-heading>

Role tailored to my homelab environment for switching ExpressVPN connection location on linux openvpn client

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see ```defaults/main.yml```)
```shell
service: openvpn-client@client
config_file: /etc/openvpn/client/client.conf
location: usa-sanfrancisco
```
## Dependencies

None

## Example Playbook
```yaml
    - hosts: all
      roles:
        - <role name>
```

## License

MIT

## Author Information

This role was created in 2022 by [Lee Woodhouse](https://www.leewoodhouse.com/)
