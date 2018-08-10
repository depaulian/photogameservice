# Validate Email

Used to check if the email address is already in use

**URL** : `validate-username/{q}`

**Method** : `GET`

**Auth required** : NO

**URL Params**

```json
{
    "email": "[valid email  should be unique]",
}
```

**Data Params**

```NONE

```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
    "status_code":1,
    "status_message":"Username Available"
}
```

## Success Response

**Code** : `401 UNAUTHORIZED`

**Content example**

```json
{
    "status_code":0,
    "status_message":"Username Address already taken"
}
```