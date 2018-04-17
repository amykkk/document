# Sync files from linux to windows
## Install PUTTY

Copy the whole folder from remote linux to local windows

C:\Program Files (x86)\PuTTY>pscp.exe -r root@10.xx.xx.xx:/home/user-workstation/workspace workspace

# Unset apt-get install proxy on ubutnu 16.04
Please search if you set the http_proxy and https_proxy
http_proxy="http://web-proxy.xx.xx.xx:8080/"
https_proxy="http://web-proxy.xx.xx.xx:8080/"
ftp_proxy="http://web-proxy.xx.xx.xx:8080/"

Delete the proxy setting line from the file:
/etc/apt/apt.conf.d
/etc/environment

Now run : suto atp-get install 
OK.

# Set/Unset curl proxy on ubuntu
export http_proxy

export https_proxy 

unset http_proxy

unset https_proxy

