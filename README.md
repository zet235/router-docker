
- run 

``` bash
docker run --name binwalk -d --privileged \
    -h binwalk \
    -v /etc/localtime:/etc/localtime:ro \
    zet235/binwalk
```
