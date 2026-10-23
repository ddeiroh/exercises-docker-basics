FROM ubuntu:24.04

RUN apt-get update && apt-get install curl -y

COPY --chmod=755 script.sh .

CMD ["./script.sh"]
