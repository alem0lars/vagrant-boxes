# Windows hacking

Windows box for hacking, testing, etc..

## Dependencies

### Old vagrants

If using vagrant `< 1.6` it requires the windows plugin:

```
$ vagrant plugin install vagrant-windows
```

### First time setup

When you use this box setup for the first time, if you haven't already added the
underlying box to vagrant you need to add it:

```ShellSession
$ vagrant box add opentable/win-8.1-core-amd64-nocm https://vagrantcloud.com/opentable/boxes/win-8.1-core-amd64-nocm/versions/1.0.0/providers/virtualbox.box
```
