# docker-gcloud

an alpine docker image with [`google-cloud-sdk`](https://cloud.google.com/sdk/)

## how to

### install

install `docker`, then

```shell
git clone https://github.com/ahdinosaur/docker-gcloud
```

### build

```shell
docker build -t ahdinosaur/gcloud .
```

### run

```shell
docker run -i -t ahidnosaur/gcloud help
```

### publish

```shell
docker push ahdinosaur/gcloud
```
