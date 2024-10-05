---
id: 1727937775-BDZA
aliases:
  - Matrix Specification
tags: []
---

# Matrix Specification

>[!note]
> Specs online link [spec.matrix.org](spec.matrix.org)

- Provides an open decentralized [pubsub layer](1727938545-IKYZ.md) for securely publishing and subscribing to JSON objects

## Users
- unique `user_id`

## Devices
- unique `device_id` per session
- We can reuse the `device_id` if state consists for for mobile applications
- but if we don't it will create `device_id` for every instance. Ex: in web browser for everytab it will create new device_id. To manage this, we can craete a unique `device_id` and store it in local store, so everytime thee browser opens the client in any tab, it will be registered as same device

## Room
- Rooms ids have aliases so that it will be in human readable form.
- But Room aliases can point to different Ids, so we use room_ids as those are uniqe identifiers for communication with namespace server.

