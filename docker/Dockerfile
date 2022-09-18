FROM alpine

LABEL creator="SecorD >> 1package"
LABEL url="📦 All in https://t.me/OnePackage"

WORKDIR root

RUN apk add -U --no-cache geth

EXPOSE 8545 30303

ENTRYPOINT ["geth"]

