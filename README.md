# CHANGELOG

## prometheus-operator

```sh
export TAG=0.1.20240704
make image OS=linux GOARCH=amd64 TAG=$TAG IMAGE_OPERATOR=ghcr.io/appscode-gcp-mp/ace-mp/prometheus-operator
docker push ghcr.io/appscode-gcp-mp/ace-mp/prometheus-operator:$TAG
```
