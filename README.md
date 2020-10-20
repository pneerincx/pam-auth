# pam-auth

Based on: https://github.com/ICS-MU/pam_oauth2_device/

## Usage

```
# initialize
#vagrant init?
vagrant up

# to shell into the vm
vagrant ssh
# for ansible provisioning
vagrant provision

# Test authentication flow in vm
pamtester -v pamtester vagrant authenticate

# stop and remove the vm
vagrant halt
vagrant destroy
```

