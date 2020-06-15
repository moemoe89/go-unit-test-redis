[![Build Status](https://travis-ci.org/moemoe89/go-unit-test-redis.svg?branch=master)](https://travis-ci.org/moemoe89/go-unit-test-redis)
[![codecov](https://codecov.io/gh/moemoe89/go-unit-test-redis/branch/master/graph/badge.svg)](https://codecov.io/gh/moemoe89/go-unit-test-redis)
[![Go Report Card](https://goreportcard.com/badge/github.com/moemoe89/go-unit-test-redis)](https://goreportcard.com/report/github.com/moemoe89/go-unit-test-redis)

# GO-UNIT-TEST-REDIS #

Example Mock Unit Test for Redis in Golang

## Directory structure
Your project directory structure should look like this
```
  + your_gopath/
  |
  +--+ src/github.com/moemoe89
  |  |
  |  +--+ go-unit-test-redis/
  |     |
  |     +--+ main.go
  |        + repository/
  |        |
  |        +--+ repository.go
  |           + repository_test.go
  |
  +--+ bin/
  |  |
  |  +-- ... executable file
  |
  +--+ pkg/
     |
     +-- ... all dependency_library required

```

## Setup

* Setup Golang <https://golang.org>
* Under `$GOPATH`, do the following command :
```
$ mkdir -p src/github.com/moemoe89
$ cd src/github.com/moemoe89
$ git clone <url>
$ mv <cloned directory> go-unit-test-redis
```

## How to Run Test
```
$ go test ./...
```

## License

MIT