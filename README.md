# ansible-intersight-nxos
Ansible playbook to claim nxos devices in Intersight

# Available variables

| Variable | Description |
| --- | ---|
| intersight_src | The source interface to be used on the NXOS device to connect to Intersight. If unset ignored.|
| intersight_vrf | The source VRF to be used on the NXOS device to connect to Intersight. If unset ignored.|
| intersight_proxy_host | The proxy ip/DNS to be used on the NXOS device to connect to Intersight. If unset ignored.|
| intersight_proxy_port | The proxy port to be used on the NXOS device to connect to Intersight. If unset ignored.|
| internet_proxy_https | The proxy to be used for your ansible execution ENV to connect to Intersight. If unset ignored. |
| api_key_id | The API key to connect to Intersight|
| api_private_key | The filename referring to the private key to connect to Intersight |

# Dependencies

See collections/requirements.yml and install with ansible-galaxy

```
ansible-galaxy install -r requirements.yml
```
