# pompa

Ultimate spear-phishing toolkit - sample docker setup (Linux-compatible)

## Prerequisites

You will need the following things properly installed on your computer:

* [Git](https://git-scm.com/)
* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)

## Installation

* `git clone https://github.com/m1nl/pompa-docker.git`
* `cd pompa-docker`
* `git submodule init`
* `git submodule update --checkout`
* `./generate_secrets.sh`

## Configuration

Look for config files in the following directories:

* app/config
* web/config
* web/nginx
* redis

## Building and running

* `docker-compose build`
* `docker-compose up`

## Further Reading / Useful Links

* [pompa-api](https://github.com/m1nl/pompa-api)
* [pompa](https://github.com/m1nl/pompa)
* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)

## License
`pompa` is released under the terms of [lgpl-3.0](LICENSE).

## Author

Mateusz Nalewajski

## Commercial support / professional services

Please contact me directly at mateusz-at-nalewajski-dot-pl
