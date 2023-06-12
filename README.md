# iProxy

Simple TCP proxy software. Proxy any TCP services in the LAN to public network, for example, remote desktop for windows[RDP TCP port: 3389],  SSH for Linux[TCP port: 22]

https://blog.csdn.net/qq_30812427/article/details/131063404

## Features

+ TCP port proxy
+ User management, new, user password  change, email binding
+ Device list, rename and delete
+ Proxy management, add a new proxy, Change proxy ipAddress for another pc's service in the LAN
+ Free for personal user

## components
+ iProxy-server: user management, proxy session management, session tansfering, security
+ iProxy-host: proxy session client, 
+ iProxy-client, ui for iProxy, windows only
|components|windows|linux|macos|
|---|---|---|---|
|iProxy-server|yes|yes|todo|
|iProxy-host|yes|yes|todo|
|iProxy-client[UI]|yes|todo|todo|
## Usage

+ Download release package: iproxy-client.zip
+ Run iproxy-client.exe
+ Register a new user
+ Sign in to server
