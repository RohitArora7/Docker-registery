# Docker-registery

```bash

docker pull registry

run -d -p 5000:5000 registry


docker pull busybox

docker tag busybox localhost:5000/busybox

docker push localhost:5000/busybox 


docker rmi busybox localhost:5000/busybox



docker pull localhost:5000/busybox

```
