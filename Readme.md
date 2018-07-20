# Build strngsvc
godep go build

# Install strinsvc to $GOPATH/bin
godep go install

# Update dependencies - updates godeps.json
go get <packagenames>
godep save
