# netplayjs-server

![](https://github.com/rameshvarun/netplayjs-server/actions/workflows/node.js.yml/badge.svg)

A basic matchmaking server. Game updates are sent peer-to-peer and thus don't go through this server.


```
docker run --publish 80:3000 varunramesh/netplayjs-server:0.0.2
```