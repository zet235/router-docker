docker run --name binwalk -d \
    -h binwalk \
    -v /etc/localtime:/etc/localtime:ro \
    zet235/binwalk