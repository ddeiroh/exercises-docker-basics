FROM ubuntu:noble

ENV PATH=$PATH:/opt/go/bin
ENV PORT=8080

ADD --checksum=sha256:65efbc80fdc1fa2cd2631cad5b481777a68e8725f34e89f50fc6ac714e379b40 --unpack=true https://dl.google.com/go/go1.27.3.linux-amd64.tar.gz /opt
WORKDIR /myapp
COPY . .
RUN go build
CMD ["./server"]
