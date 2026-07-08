# ReqRes API Testing
## Test 1
Endpoint: https://reqres.in/api/users/2
Method: GET
Status Code: 200 OK
Response:
{
    "page": 2,
    "per_page": 6,
    "total": 12,
    "total_pages": 2,
    "data": [
        {
            "id": 7,
            "email": "michael.lawson@reqres.in",
            "first_name": "Michael",
            "last_name": "Lawson",
            "avatar": "https://reqres.in/img/faces/7-image.jpg"
        },
        {
            "id": 8,
            "email": "lindsay.ferguson@reqres.in",
            "first_name": "Lindsay",
            "last_name": "Ferguson",
            "avatar": "https://reqres.in/img/faces/8-image.jpg"
        },
        {
            "id": 9,
            "email": "tobias.funke@reqres.in",
            "first_name": "Tobias",
            "last_name": "Funke",
            "avatar": "https://reqres.in/img/faces/9-image.jpg"
        },
        {
            "id": 10,
            "email": "byron.fields@reqres.in",
            "first_name": "Byron",
            "last_name": "Fields",
            "avatar": "https://reqres.in/img/faces/10-image.jpg"
        },
        {
            "id": 11,
            "email": "george.edwards@reqres.in",
            "first_name": "George",
            "last_name": "Edwards",
            "avatar": "https://reqres.in/img/faces/11-image.jpg"
        },
        {
            "id": 12,
            "email": "rachel.howell@reqres.in",
            "first_name": "Rachel",
            "last_name": "Howell",
            "avatar": "https://reqres.in/img/faces/12-image.jpg"
        }
    ],
    "support": {
        "url": "https://benhowdle.im/first-cto-playbook?utm_source=reqres&utm_medium=json&utm_campaign=referral",
        "text": "Become a better CTO. A playbook of painful stories and practical advice from a two-time startup CTO."
    },
    "_meta": {
        "powered_by": "ReqRes",
        "docs_url": "https://app.reqres.in/documentation",
        "upgrade_url": "https://app.reqres.in/upgrade",
        "example_url": "https://app.reqres.in/examples/notes-app",
        "variant": "v1_a",
        "message": "Your data persists here. Add auth, logs, and custom schemas to build a real backend.",
        "cta": {
            "label": "See example app",
            "url": "https://app.reqres.in/examples/notes-app"
        },
        "context": "legacy_success"
    }
}
## Test 2
Endpoint: https://reqres.in/api/users
Method: POST

Request Body:
{
  "name":"Ratish",
  "job":"SDET"
}

Status Code: 201 Created
Response:
{
    "name": "Ratish",
    "job": "SDET",
    "id": "712",
    "createdAt": "2026-07-08T18:39:17.284Z",
    "_meta": {
        "powered_by": "ReqRes",
        "docs_url": "https://app.reqres.in/documentation",
        "upgrade_url": "https://app.reqres.in/upgrade",
        "example_url": "https://app.reqres.in/examples/notes-app",
        "variant": "v1_a",
        "message": "Your data persists here. Add auth, logs, and custom schemas to build a real backend.",
        "cta": {
            "label": "See example app",
            "url": "https://app.reqres.in/examples/notes-app"
        },
        "context": "legacy_success"
    }
}
## Test 3
Endpoint: https://reqres.in/api/users/2
Method: PUT

Request Body:
{
  "name": "Ratish",
  "job": "Senior SDET"
}

Status Code:200 OK
Response:
{
    "name": "Ratish",
    "job": "Senior SDET",
    "updatedAt": "2026-07-08T18:41:47.937Z",
    "_meta": {
        "powered_by": "ReqRes",
        "docs_url": "https://app.reqres.in/documentation",
        "upgrade_url": "https://app.reqres.in/upgrade",
        "example_url": "https://app.reqres.in/examples/notes-app",
        "variant": "v1_a",
        "message": "Your data persists here. Add auth, logs, and custom schemas to build a real backend.",
        "cta": {
            "label": "See example app",
            "url": "https://app.reqres.in/examples/notes-app"
        },
        "context": "legacy_success"
    }
}
## Test 4
Endpoint: https://reqres.in/api/users/2
Method: PATCH

Request Body:
{
  "name": "Ratish",
  "job": "Lead SDET"
}

Status code: 200 OK
Response:
{
    "name": "Ratish",
    "job": "Lead SDET",
    "updatedAt": "2026-07-08T18:44:33.674Z",
    "_meta": {
        "powered_by": "ReqRes",
        "docs_url": "https://app.reqres.in/documentation",
        "upgrade_url": "https://app.reqres.in/upgrade",
        "example_url": "https://app.reqres.in/examples/notes-app",
        "variant": "v1_a",
        "message": "Your data persists here. Add auth, logs, and custom schemas to build a real backend.",
        "cta": {
            "label": "See example app",
            "url": "https://app.reqres.in/examples/notes-app"
        },
        "context": "legacy_success"
    }
}
## Test 5
Endpoint: https://reqres.in/api/users/2
Method: HEAD

Request Body:
None

Status Code: 200 OK
Response:
None
## Test 6
Endpoint: https://reqres.in/api/users
Method: OPT

Request Body:
None

Status Code: 204 No Content
Response:
None
## Test 7
Endpoint: https://reqres.in/api/users/2
Method: DELETE

Request Body:
None

Status Code: 204 No Content
Response:
None
