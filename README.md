# Sillok

Sillok means the annals in Korean. That is generally "The Annals of the Joseon Dynasty".
However, This repository is service for "The Annals of the Repulic of Korea".

## Sturcture

## Event

| Field        | Type        | Description            | Required | Default     |
| ------------ | ----------- | ---------------------- | -------- | ----------- |
| datetime     | Date String | Date and Time happened | o        | createdAt   |
| title        | String      |                        | o        |             |
| description  | String      |                        | o        |             |
| createdAt    | Date String |                        | o        | Posted time |
| updatedAt    | Date String |                        | o        | Posted time |
| authors      | User[]      |                        | o        | []          |
| comments     | Comment[]   |                        |          | []          |
| tags         | String[]    |                        |          |             |
| deprecatedAt | Date String |                        |          |             |
| credibility  | Number      |                        | o        | 0           |

## User

| Field       | Type         | Description | Required | Default |
| ----------- | ------------ | ----------- | -------- | ------- |
| userId      | UUID String  |             | o        | o       |
| username    | String       |             | o        | o       |
| isVerified  | Boolean      |             | o        | false   |
| email       | Email String |             | o        | o       |
| credibility | Number       |             | o        | 0       |


