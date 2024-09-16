# AxLabs: cloud-init scripts

Public cloud-init files for VMs.

If you don't know much about cloud-init, [start here](https://cloudinit.readthedocs.io/en/latest/).

## Example

This is what you'll need to input in your Cloud's cloud-init script:

```
#cloud-config
#include-url:
  - https://raw.githubusercontent.com/AxLabs/cloud-init/main/cloud-init-ssh.yaml
  - https://raw.githubusercontent.com/AxLabs/cloud-init/main/cloud-init-swap-config.yaml
```

If you would like to add/remove scripts, add them as an URL.