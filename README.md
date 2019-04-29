# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/k8s-dns-dnsmasq-nanny-amd64:${VERSION}
docker tag hawsers/k8s-dns-dnsmasq-nanny-amd64:${VERSION} k8s.gcr.io/k8s-dns-dnsmasq-nanny-amd64:${VERSION}
docker rmi hawsers/k8s-dns-dnsmasq-nanny-amd64:${VERSION}
```
