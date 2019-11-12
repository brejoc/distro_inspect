# Distro Inspect

Here is an example for leap:

```
$ docker-compose up leap
Starting distro_inspect_leap_1 ... done
Attaching to distro_inspect_leap_1
leap_1        | ('openSUSE Leap', '15.1', '')
leap_1        | ========================================
leap_1        | id:       opensuse-leap
leap_1        | name:     openSUSE Leap
leap_1        | like:     suse opensuse
leap_1        | name:     openSUSE Leap
leap_1        | version:  15.1
leap_1        | 
distro_inspect_leap_1 exited with code 0
```

This is all about the `distro` module from Python and what it might return for various distributions. You can choose from the following list:

* centos7
* centos8
* debian
* fedora
* leap
* tumbleweed
* rhel7
* rhel8
* ubuntu
