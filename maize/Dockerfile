FROM golang:latest

WORKDIR /app

COPY ./ /app

RUN go mod download

#RUN go get github.com/githubnemo/CompileDaemon
#ENTRYPOINT CompileDaemon --build="go build -o main ./go" --command=./main
ENTRYPOINT ["go", "run", "./go"]
