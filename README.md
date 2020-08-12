# Overview

asdf version manager plugin for oq

- Find asdf here: https://github.com/asdf-vm/asdf
- Find oq here:   https://github.com/Blacksmoke16/oq
- oq overview: https://dev.to/blacksmoke16/oq-a-portable-performant-jq-wrapper-18ka


# Supported OS's

Currently only Linux is supported.


# Requirements

- curl
- jq
- bash
- sed


# Install
```bash
asdf plugin-add oq git@github.com:ben0x4a/asdf-oq.git
asdf list-all oq

LATEST=$(asdf list-all oq | tail -1)
asdf install oq ${LATEST}
asdf global oq ${LATEST}
oq --version
```
