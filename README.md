# VPN-Proxy-Example-Gluetun
An example on how to set up a VPN proxy using a docker container and gluetun, the docker coompose file needs only set your VPN provider user and password, but doublecheck that the port is not already being used. 
If you want to deploy this on a server I am quite happy with the use of Portainer (this way you can interact with your containers on a friendly manner without having to set up a desktop environment for the whole server).

In this example we can set up a VPN proxy so our connections adressed at this port (in the docker compose file) are directed through the Netherlands (or any country your VPN provider supports).
For further details on configuration or available providers see: https://github.com/qdm12/gluetun

An easy way to ckech or direct the traffic of your web browser (Firefox) through the proxy is: Settings > Network configuration > Manual Proxy Configuration: Write the IP and port of your Proxy
Now your connections are redirrected through the VPN :)
