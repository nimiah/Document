# install gnostic
go get -u github.com/googleapis/gnostic
go get -u github.com/googleapis/gnostic-grpc

# generate command
```sh
$ gnostic --grpc-out=examples/bookstore examples/bookstore/bookstore.yaml
```
