# docker-tools
Handy scripts make your Docker even better

## Installation

```bash
git clone git@github.com:kcyeu/docker-tools.git
mkdir -p ${HOME}/bin
cp docker-tools/bin/* ${HOME}/bin
export PATH=${HOME}:${PATH}
```

## Usage

| Command                   | Description                                               |
|---------------------------|-----------------------------------------------------------|
| ```docker-pull-all```     | pull ```latest``` version of each local image             |
| ```docker-rmi-untagged``` | remove untagged images (e.g. repository name is "<none>") |
