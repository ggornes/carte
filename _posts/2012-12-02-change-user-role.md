---
category: User Services
url_path: '/users/:id/change_role'
title: 'Change user role'
type: 'PUT'

layout: null
---

This method allows users to retrieve stuff.

### Request

* **`:id`** is the id the user to change role.

* The **headers** must include a **valid authentication token**.

```Authentication: bearer TOKEN```

* **The body can't be empty** and must include at least the `Id`, `UserName`, `UserEmail` and the `UserRole` attributes.


```{
    "Id":2
    "UserName": "test2",
    "UserEmail": "test2@mail.com",
    "UserRole": "admin"
}```

### Response

Sends back.

```Status: 204 NO CONTENT```


For errors responses, see the [response status codes documentation](#response-status-codes).
