#Role Variables
users_deleted: []
  - cmc.abc
  - cmc.dce
  - cmc.143


users:
  - cmc.tvsinh
  - cmc.nbtien
  - cmc.cvhai

#TCP Wrapper
list_ip_access:
  - '10.0.0.1       # Ansible'
  - '192.168.10.110 # VDI cmc.tvsinh'
  - '10.123.10.10   # VDI cmc.nbtien'


