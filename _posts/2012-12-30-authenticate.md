---
category: User Services
url_path: '/users/authenticate'
title: 'Authenticate'
type: 'POST'

layout: null
---

This method allows users to authenticate

### Request

* Header



* The body must include a **UserToken**.

```{
    "UserToken": "userToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1bmlxdWVfbmF
    tZSI6IjEiLCJuYmYiOjE1ODkwOTI4MjgsImV4cCI6MTU4OTY5NzYyOCwiaWF0IjoxNT
    g5MDkyODI4fQ.u5A7Q7Wp1HQIg-vb_PdQi7D6ZxnGt-ptp4zDfHBP8FA"
}```

### Response

Sends back a collection of things.

```Status: 200 OK```
```{
    "userToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1bmlxdWVfbmF
    tZSI6IjEiLCJuYmYiOjE1ODkwOTI4MjgsImV4cCI6MTU4OTY5NzYyOCwiaWF0IjoxNT
    g5MDkyODI4fQ.u5A7Q7Wp1HQIg-vb_PdQi7D6ZxnGt-ptp4zDfHBP8FA"
}```

For errors responses, see the [response status codes documentation](#response-status-codes).
