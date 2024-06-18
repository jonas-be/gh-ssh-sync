# Github SSH key sync

This script syncs your ssh keys to your authorized keys file.

## Install

1. Download the script
2. Move it to bin. *For example to `/usr/local/bin`*


## Configuration

You only need to set your ``GITHUB_USER`` as environment variable, the rest is optional.

```bash
# Required
export GITHUB_USER=jonas-be
# Optional
export FILE=.ssh/authorized_keys
export GH_SYNC_MARKER="# Github ssh key sync"
```
