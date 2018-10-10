## Get all workouts for a User

Returns all workouts for the authenticated user.

### HTTP Request

`GET http://api.wahooligan.com/cloud-api/workouts`

### Query Parameters

Parameter | Type | Required | Default | Description
--------- | ---- | -------- | ------- | -----------
after | integer | no | 0 | If set to true, the result will also include cats.
limit | integer | yes | 50 | If set to false, the result will include kittens that have already been adopted.
