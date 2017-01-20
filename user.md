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
  "current_profile_id": 123,
  "video_evaluation_credits": 123 // When user has no video credits, return 0
}
```

:large_blue_circle: Set current user info.

```javascript
POST /user
```

### Request params
```javascript
{
  "current_profile_id": 123
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