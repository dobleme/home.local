# home.local

This is my ad hoc playbook to setup a local machine. As you can see is not using
roles nor trying to generalize anything, just a bunch of very specific tasks.

Just tested with `Fedora Workstation 37`.

## Requirements

- git
- python 3
- ansible

```sh
$ git clone https://github.com/dobleme/home.local.git
$ ansible-galaxy install -r requirements.yml
```

## TODO
- [ ] Disable some desktop entries
- [x] Install user fonts
- [ ] Install JetBrains IDEs
- [ ] Add GNOME extensions
- [ ] Add VSCode settings/extensions
- [ ] Install GTK themes/icons
- [ ] Generate and link ssh config/keys
