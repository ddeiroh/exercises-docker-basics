FROM golang:1.27.3

ENV PORT=8080

#RUN apt-get update && apt-get install -y git
WORKDIR /myapp
COPY . .
RUN go build
CMD ["./server"]
