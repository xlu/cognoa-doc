## Profile

:large_blue_circle: Get current user profiles and their associated submission details.

```javascript
GET /profiles
```
### Response
```javascript
[
  {
    "id" => 5,
    "first_name" => "Leonardo",
    "last_name" => "Green",
    "biological_sex" => "Female",
    "date_of_birth" => "2012-02-03",
    "previous_diagnoses" => [],
    "other_diagnoses" => nil,
    "created_at" => "2016-11-03T22:35:02.000Z",
    "submissions" => [
      {
        "id" => 4,
        "created_at" => "2016-11-03T22:35:03.000Z",
        "updated_at" => "2016-11-03T22:35:03.000Z",
        "submitted_at" => nil,
        "unscorable_at" => nil,
        "questionnaire_completed" => true,
        "videos_completed" => true,
        "screening_result" => "low_risk",
        "status" => "Complete"
      }, 
      {
        "id" => 5,
        "created_at" => "2016-11-03T22:35:03.000Z",
        "updated_at" => "2016-11-03T22:35:03.000Z",
        "submitted_at" => "2016-11-03T22:35:03.000Z",
        "unscorable_at" => nil,
        "questionnaire_completed" => true,
        "videos_completed" => true,
        "screening_result" => "high_risk",
        "status" => "Pending"
      }, 
      {
        "id" => 6,
        "created_at" => "2016-11-03T22:35:03.000Z",
        "updated_at" => "2016-11-03T22:35:03.000Z",
        "submitted_at" => nil,
        "unscorable_at" => "2016-11-03T22:25:03.000Z",
        "questionnaire_completed" => true,
        "videos_completed" => true,
        "screening_result" => "high_risk",
        "status" => "Unscorable"
      }
    ]
  }
]
```
