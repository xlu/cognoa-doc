## User

:large_blue_circle: Get current user info.

```javascript
GET /user
```

### Response
```javascript
{
  "id": 123,
  "first_name" : "...",
  "last_name": "...",
  "current_profile_id": 123
}
```

:large_blue_circle: Set current user info.

```javascript
POST /account
```

### Request params
```javascript
{
  "user": {
    "current_profile_id": 123
  }
}
```

| Params        | Type           |   Description|
| :------------- |:-------------| :-----|
| current_profile_id     | Integer | Active child profile id |


### Response
#### When successful
```javascript
200 OK
```

#### When failed
```javascript
422 unprocessable_entity
```