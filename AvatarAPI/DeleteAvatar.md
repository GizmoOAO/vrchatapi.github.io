# Delete Avatar

This API allows you to delete an avatar. This API will not actually delete the character file but will sets it's release status to hidden.

!> Only works if the avatar is yours!

## Request Method
DELETE

## Endpoint
https://api.vrchat.cloud/api/1/avatars/[ID]

ID - the avatar id

## Requires Authentication
Yes (See [here](/Authorization.md) for details)

## Returns

[`Avatar object`](/Objects/Avatar.md#avatar-object)
