# Personal Playbooks

Just a few playbooks to prepare a machine for myself.

## Using sudo
Most environments I use for labs have sudo setup without a password, however, this doesn't necissarily work well on a workstation. You can feed ansible a sudo password with the following options:

```shell
$ ansible-playbook --ask-become-pass playbook.yml
```

## Starting emacs without x
I don't know why I install the x11 version of emacs on my workstation. Here's how to start it without x

```shell
$ emacs -nw
```