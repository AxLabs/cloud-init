# AxLabs: cloud-init scripts

Public cloud-init files for VMs.

## Example

```
#cloud-config
#include-url:
  - https://raw.githubusercontent.com/AxLabs/cloud-init/main/cloud-init-ssh.yaml
  - https://raw.githubusercontent.com/AxLabs/cloud-init/main/cloud-init-swap-config.yaml
```