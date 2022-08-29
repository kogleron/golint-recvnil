# golint-recvnil

Another golang linter that checks that there is a check for nil for the dereferenced receiver in a method.

## Installation

```shell
go install github.com/kogleron/golint-recvnil/cmd/recvnil@latest
```

## How to run

```shell
go vet -vettool=$(which ./bin/recvnil) ./...
```

## TODO

- [x] Show in report the position of a receiver derederencing instead of a method.
- [ ] Add ignore list.