# routerproxy
A simple project to be able to connect to my old HGW-2501GN-R2 router that uses old SSL ciphers

Usage:

`docker build -t routerproxy .`

`docker run -p 81:81 routerproxy`

And then access http://localhost:81/cgi-bin/mhs/html/logIn_mhs.asp from your favourite modern browser to talk to your router in http.
