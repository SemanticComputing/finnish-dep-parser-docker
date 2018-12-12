# Finnish-dep-parser Docker

Docker container for [Finnish dependency parser](https://github.com/TurkuNLP/Finnish-dep-parser) that can be ran as an arbitrary (non-root) user. Based on https://github.com/samisalkosuo/finnish-dep-parser-docker

Available also in Docker Hub: [secoresearch/finnish-dep-parser](https://hub.docker.com/r/secoresearch/finnish-dep-parser/).

## Build

`docker build -t secoresearch/finnish-dep-parser .`

## Run

`docker run --rm -it -p 9876:9876 --name finnish-dep-parser secoresearch/finnish-dep-parser`

The same command can be used to pull and run the container from Docker Hub (no need to build the image first).

## Usage

Make a HTTP GET request:

http://localhost:9876/?text=...

See [further instructions](https://github.com/samisalkosuo/finnish-dep-parser-docker).
