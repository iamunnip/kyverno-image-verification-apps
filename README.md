## Building Image

```
docker image build -f Dockerfile_Signed -t username/app-signed:v1

docker image build -f Dockerfile_Unsigned -t username/app-unsigned:v1
```

## Pushing Image to Registry

```
docker image push username/app-signed:v1

docker image push username/app-unsigned:v1
```