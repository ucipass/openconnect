# openconnect
Openconnect VPN Docker container with local SSH and Web proxy service 
3128 web proxy port
2222 openssh server for tunneling

    docker run --rm -e HOST=<HOSTNAME> -e USER=<USER> --name oc -it -p 3128:3128 -p 2222:22 --privileged ucipass/openconnect
