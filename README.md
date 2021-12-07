# asdf-svcat
Plugin for [asdf](https://github.com/asdf-vm/asdf) Package Manager, install [camel-k](https://github.com/kubernetes-sigs/service-catalog/) cli.

## Install

Look for the Latest Release of [kubernetes-sigs/service-catalog](https://github.com/go-task/task/releases) Commandline Plugin. 

```sh
asdf plugin-add svcat https://github.com/nolte/asdf-svcat.git

asdf install svcat 0.3.1
```

For the latest release take a look to the [Github releases](https://github.com/kubernetes-sigs/service-catalog/releases).

## Development


Direct call, for local development.
```sh
ASDF_INSTALL_TYPE=test \
  ASDF_INSTALL_VERSION=0.3.1 \
  ASDF_INSTALL_PATH=/tmp/plugin \
  ./bin/install
```
