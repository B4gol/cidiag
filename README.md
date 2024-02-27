# circleci-vsscall

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/vsseclab/circleci-vsscall/tree/vsscall.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/vsseclab/circleci-vsscall/tree/vsscall)

Bash script to run diag commands in a build

## Supported OS

Uses `uname -s` to fetch OS

* Linux
* Darwin

## Modules

### OS

* Runs `ps aux` on both Darwin and Linux

### Package

* Runs `dpkg -l` on Linux
* Runs `brew list --versions` on Darwin

