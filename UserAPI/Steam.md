# Steam

This API allows you to get user data from a Steam account

## Request Method
POST (as json)

## Endpoint
    https://api.vrchat.cloud/api/1/user/steam

## Requires Authentication
No

## Parameters

Field | Type | Optional | Description
------|------|----------|------------
steamTicket | string | No | The Steamworks ticket from the VRChat game

## Returns

[`Current User object`](/Objects/User.md#current-user-object)

The endpoint also return an auth cookie that can be used until the socket is disconnected from the web server
