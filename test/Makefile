lint:
	GOOS=darwin golangci-lint run ./...
	GOOS=linux golangci-lint run ./...

test:
	go test -p 1 -v ./...

benchmark:
	go test -benchmem -run=^$$ -bench .
