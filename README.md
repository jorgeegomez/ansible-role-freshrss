# Ansible role that configures FreshRSS in a new server or container

Based on a snippet published by [@oupala][1]

To be used with Ansible-pull, typically on a newly created container,
running Ubuntu 20.04, like this:

```console
root@freshrss:~# apt install ansible
...
Setting up ansible (2.9.6+dfsg-1) ...
...
root@freshrss:~# ansible-pull -U "https://github.com/jorgeegomez/ansible-role-freshrss.git"
```

[1]: https://github.com/oupala 
