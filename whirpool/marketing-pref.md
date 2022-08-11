# Update Person Preferences

Update a Person Marketing Preferences [using D&G PersonId]

**URL** : ``

**Method** : `PATCH`

**Auth required** : YES

**Permissions required** : None

**Data constraints** : `{
country:
personId:
marketing {
        post: boolean or null
        email: boolean or null
        telephone: boolean or null
        sms: boolean or null
}
}
`

## Success Responses

**Condition** : Person Marketing Preferences successfully updated.

**Code** : `200 OK`

**Content** : `{[]}`

## Other Responses

**Condition** : Person not found matching PersonId.

**Code** : `404`

**Content** : `{[]}`

**Condition** : Update not successful.

**Code** : `404`

**Content** : `{[]}`