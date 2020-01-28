https://github.com/rapid7/metasploit-framework/blob/master/Dockerfile

sudo docker run --rm -it -p 443:443 -v ~/.msf4:/root/.msf4 -v /tmp/msf:/tmp/data remnux/metasploit