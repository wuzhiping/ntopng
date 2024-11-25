# ntopng
https://www.ntop.org/products/traffic-analysis/ntop/

# docker
docker run --rm -it --net=host -p 3333:3000 ntop/ntopng.dev -i eth0

# cacti
## https://github.com/babyfenei/docker-cacti/blob/master/README_ZH.md
docker run --rm -it -p 8888:80 -e TZ=Asia/Shanghai shawoo/cacti
