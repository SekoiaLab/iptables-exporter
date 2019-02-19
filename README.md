# Purpose
This is just a repository to pack the code of the prometheus exporter https://github.com/retailnext/iptables_exporter


# Running 
To run this docker properly, you need to add some capabilities. 

```bash 

sudo docker run --rm -it -p 9455:9455 --cap-add DAC_READ_SEARCH --cap-add NET_ADMIN --cap-add NET_RAW sekoialab/iptables_exporter
```
