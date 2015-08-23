![docker-tools logo](docker-tools-logo.png =400x)

# docker-tools
Handy scripts make your Docker even better

## Installation

```bash
git clone git@github.com:kcyeu/docker-tools.git
cd docker-tools && make install
```

Then add ```~/bin/``` to your ```$PATH```.

## Usage

| Command                      | Description                                               |
|------------------------------|-----------------------------------------------------------|
| ```docker-upgrade```         | upgrade docker engine                                     |
| ```docker-pull-all```        | pull ```latest``` version of each local image             |
| ```docker-rmi-untagged```    | remove untagged images (e.g. repository name is "<none>") |
| ```docker-install```         | install or update local docker                            |
| ```docker-compose-install``` | install the latest docker-compose                         |
