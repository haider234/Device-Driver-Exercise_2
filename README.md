# Device-Driver-Exercise_2

A simple netcat-based chat application, can be used on a local network when the internet connection goes down and other chat services are unavailable.

First person runs server.sh

Second person connects to first process by running   nc 192.168.0.1 9999

where, 192.168.0.1 is the Ip address of first person and 9999 is port number

BashChat defaults to port 9999, but this can be configured on the command line to avoid conflicts and allows running multiple BashChat sessions from the same computer. e.g. Running on port 9998: server.sh 9998
