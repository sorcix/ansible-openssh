# OpenSSH role

## Required configuration

This role aims to have sane defaults, which may change in the future to keep up with
security standards. The only setting that you **have** to change is the list of SSH keys that
are allowed to log in as the `root` user.

```
ssh_root_keys:
  - "ssh-rsa keeeeeeeey comment"
```
