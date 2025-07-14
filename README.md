# NVIDIA GPU Operator for rename version

```shell
docker build \
  --build-arg http_proxy="" \
  --build-arg https_proxy="" \
  --build-arg all_proxy="" \
  --build-arg GOLANG_VERSION=1.24.3 \
  --build-arg VERSION=v25.3.1 \
  --build-arg GIT_COMMIT=$(git rev-parse HEAD) \
  -t <repo>:<tag> \
  -f Dockerfile.validator .
```
