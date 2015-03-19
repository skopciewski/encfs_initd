# Overview

The Gentoo init script for mounting the encfs user dirs.

## Usage

```bash
cp init.d/encfs /etc/init.d/encfs
cp conf.d/encfs.example /etc/conf.d/encfs
rc-update add encfs default
```

## Configuration

Edit the `/etc/conf.d/encfs` and set the ENCFS_MOUNPOINTS array with the rows containimg:
* user
* source dir
* destination dir
* encfs password
