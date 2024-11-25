# ntopng
https://www.ntop.org/products/traffic-analysis/ntop/

# docker
## https://github.com/ntop/docker-ntop
## docker run --rm -it --net=host -e NTOP_CONFIG="-r 127.0.0.1:7379 -i eth0 -w 0.0.0.0:3000"  ntop/ntopng:stable

# cacti
## https://github.com/babyfenei/docker-cacti/blob/master/README_ZH.md
docker run --rm -it -p 8888:80 -e TZ=Asia/Shanghai shawoo/cacti
