---
id: matrix_doc
aliases:
  - Matrix Overview
tags:
  - matrix
---

# Concepts of Matrix

for specification mentions in the [[Matrix Specification]]

## Home Server
- Host accoounts of matrix users.
- Single domain
- matrix users in the same homeserver  contain identifier in format of `@username:example.com` (Where example.com is the home-server domain)

## Client
- Softwares that can use matrix account to send or receive events from a specif homeserver
- Server to Server communication (Server-Server API / Federation API)
- Server to Client Commmiunication (Client-Server API)
- Example: Element, Fractal and etc

## AppService ( Bots and Bridges)

### Bots
- Bots are just limited and specified clients.
- Bots example is RSS bot.
    - It Subscribes a RSS feed outside of matrix client. Whenever it sees a new item in the feed , it posts that in the matrix room.

### Bridges
- It allows to connect thirdparty platform with matrix community
- Matrix user -> Other platform(puppets)
- Other platform users -> On Matrix (ghosts)


