# Tiresias
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FXuanwo%2Ftiresias.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FXuanwo%2Ftiresias?ref=badge_shield)


`Tiresias` is a tool to help you access your servers. With the support shell completion, you can use `ping production-server` or `ssh staging-server` smoothly.

## Features

- Generate ssh config
- Generate hosts files

## Quick start

Create a config file like following:

```yaml
src:
  - type: fs
    path: /path/to/source/file

dst:
  - type: ssh_config
    path: /home/xuanwo/.ssh/config
  - type: hosts
    path: /etc/hosts
```

And run:

```ssh
sudo tiresias --config ~/.tiresias/config.yaml
```

Your will see all hosts and ssh config generated.

## Installation

Get the latest tiresias for Linux from [releases](https://github.com/Xuanwo/tiresias/releases)

## LICENSE

The Apache License (Version 2.0, January 2004).


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FXuanwo%2Ftiresias.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FXuanwo%2Ftiresias?ref=badge_large)