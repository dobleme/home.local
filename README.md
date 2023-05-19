# home.local

This is my ad hoc playbook to setup a local machine. As you can see is not using
roles nor trying to generalize anything, just a bunch of very specific tasks.

It can be used with:
- Fedora Workstation `37`
- Ubuntu `22.04`

## Requirements
- git
- python 3
- python3-apt
- python3-psutil
- ansible

```sh
$ git clone https://github.com/dobleme/home.local.git
$ ansible-galaxy install -r requirements.yml
```

## TODO
- [x] Disable some desktop entries
- [x] Install user fonts
- [x] Add GNOME extensions
- [ ] Install GTK themes/icons
- [x] Generate and link ssh config/keys
- [x] Split tasks by application (term, xterm, ...)
