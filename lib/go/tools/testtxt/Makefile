BIN_NAME="testtxt"

ALL: $(BIN_NAME)

$(BIN_NAME):
	go build -o bin/$(BIN_NAME) .
	go install

.PHONY: install
install:
	go install

.PHONY: test
test:
	go test -cover -v -race
