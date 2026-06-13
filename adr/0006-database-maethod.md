# 6. Database maethod

Date: 2026-06-13

## Status

Accepted

## Context

The app we will be making will need a database to store the user information including all of the event related information and preferences.

## Decision

We will be implementing a local database within the app to store the data. This database will be unencrypted.

## Consequences

This will make it possible for users to store their planned events within the app. It will include challenges for implementation because many factors will have to be considered such as the storage method, reading/writing method and properly displaying information.