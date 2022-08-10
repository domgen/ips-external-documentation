# Update Person Preferences

Update a Person Marketing Preferences [using D&G PersonId]

<!-- **URL** : `` -->

**Method** : `PATCH`

**Auth required** : YES

<!-- **Permissions required** : None -->

**Data constraints** : 
```
{
   "personId": string,
   "marketing": {
      "post": boolean or null
      "email": boolean or null
      "telephone": boolean or null
      "sms": boolean or null
    }
}
```

## Success Responses

**Condition** : Person Marketing Preferences successfully updated.

**Code** : `204`

<!-- **Content** : 
```
{
   "message": "OK"
}
``` -->

## Other Responses

**Condition** : Person not found matching PersonId.

**Code** : `404`

**Content** : `TBD`

**Condition** : Update not successful (Bad Request).

**Code** : `400`

**Content** : `TBD`
