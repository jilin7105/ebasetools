go get -u github.com/go-bindata/go-bindata/cmd/go-bindata
cd cmd/app
go-bindata -pkg app -o assets.go ../templates/...