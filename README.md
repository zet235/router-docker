
- run 

``` bash
docker run --name router -d --privileged \
    -h router \
    -v /etc/localtime:/etc/localtime:ro \
    zet235/router
```
