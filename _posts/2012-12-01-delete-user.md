---
category: User Services
url_path: '/users/:id'
title: 'Delete a user'
type: 'DELETE'

layout: null
---

This method allows to delete a user from the database.

### Request

* **`:id`** is the id the user to delete.

* The **headers** must include a **valid authentication token**.
```Authentication: bearer TOKEN```

* The **body** is omitted.

### Response

Sends back a the deleted user details.

```Status: 200 OK```
```{
    "id": 4,
    "userName": "test500",
    "userPassword": "test500",
    "userEmail": "test500@mail.com",
    "firstName": "test500",
    "lastName": "test500",
    "userRole": "user",
    "dateCreated": "2020-05-10T16:00:53",
    "dateModified": null,
    "userFeatures": []
}```

For errors responses, see the [response status codes documentation](#response-status-codes).
