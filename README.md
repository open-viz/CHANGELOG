# CHANGELOG

## prometheus-operator

```sh
export TAG=0.1.20240704

make image OS=linux GOARCH=amd64 TAG=v0.75.2 IMAGE_OPERATOR=ghcr.io/appscode-gcp-mp/ace-mp/prometheus-operator
docker tag ghcr.io/appscode-gcp-mp/ace-mp/prometheus-operator:v0.75.2 ghcr.io/appscode-gcp-mp/ace-mp/prometheus-operator:$TAG
docker push ghcr.io/appscode-gcp-mp/ace-mp/prometheus-operator:$TAG
```
