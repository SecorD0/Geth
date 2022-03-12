FROM alpine

LABEL creator="SecorD | Let's Node"
LABEL url="https://t.me/letskynode — node Community"

WORKDIR root

RUN apk add -U --no-cache geth

EXPOSE 8545 30303

ENTRYPOINT ["geth"]

