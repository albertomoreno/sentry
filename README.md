
# sentry

[![GoDoc](https://godoc.org/github.com/altipla-consulting/sentry?status.svg)](https://godoc.org/github.com/altipla-consulting/sentry)
[![Build Status](https://travis-ci.org/altipla-consulting/sentry.svg?branch=master)](https://travis-ci.org/altipla-consulting/sentry)

Sentry client with additional functionality and helpers to complement the official one.


### Install

```shell
go get github.com/altipla-consulting/sentry
```

This library has the following dependencies:

- [github.com/getsentry/raven-go](github.com/getsentry/raven-go)
- [github.com/juju/errors](github.com/juju/errors)
- [github.com/sirupsen/logrus](github.com/sirupsen/logrus)
- [golang.org/x/net/context](golang.org/x/net/context)


### Contributing

You can make pull requests or create issues in GitHub. Any code you send should be formatted using `gofmt`.


### Running tests

Run the tests

```shell
make test
```


### License

[MIT License](LICENSE)
