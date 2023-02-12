#### Websocket configuration (server)
https://nginx.org/en/docs/http/websocket.html


proxy_set_header Upgrade $http_upgrade;
proxy_set_header Connection $connection_upgrade;
