# Go Build Bug

https://github.com/golang/go/issues/22409

Steps to repo the bug:
- `cd $GOPATH`
- `go get github.com/clintmod/goBuildBug`
- `cd $GOPATH/github.com/clintmod/goBuildBug`
- `go install ./...`

Expected:
The build to succeed.

Actual:
The build fails with the error:

go build github.com/clintmod/goBuildBug/tests: no non-test Go files in github.com/clintmod/goBuildBug/tests