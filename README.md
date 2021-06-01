# drone-clair

Drone plugin to scan docker images with [Clair](https://github.com/coreos/clair).

For the usage information and a listing of the available options please take a look at [the docs](DOCS.md).

## Build

Build the binary with the following commands:

```
go build
go test
```

## Usage

Execute from the working directory:

```
docker run --rm \
  poke/drone-clair --url http://clair.company.com --username johndoe \
  --password mysecret --scan_image python:2.7
```
