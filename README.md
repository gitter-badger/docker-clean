# Docker-Clean

[![Join the chat at https://gitter.im/killianbrackey/docker-clean](https://badges.gitter.im/killianbrackey/docker-clean.svg)](https://gitter.im/killianbrackey/docker-clean?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A simple Shell script to clean up the Docker Daemon.

## Requirements

In order to use the volume capabilities, it is required that the Docker Daemon is at least version 1.9+


## Install
    curl -s https://raw.githubusercontent.com/ZZROTDesign/docker-clean/master/docker-clean.sh |
    sudo tee /usr/local/bin/docker-clean > /dev/null && \
    sudo chmod +x /usr/local/bin/docker-clean

## License

The code is available under the [MIT License](/LICENSE).
