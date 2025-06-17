---
sidebar_position: 2
---

# GET `/v1/users/{userId}`

## Path Variable

| Path Variable | Data Type | Description  |
| ------------- | --------- | ------------ |
| userId        | number    | ID of record |

## Parameters

| Parameter | Description |
| --------- | ----------- |

## Request Schemas

| Parameter | Data Type | Description |
| --------- | --------- | ----------- |
| Path      | String    | search      |

### Request Sample

```json title=""
{
  "search": "john"
}
```

## Response Schemas

| Parameter | Data Type | Description | UI Field Mapping |
| --------- | --------- | ----------- | ---------------- |
| Path      | String    | search      | test             |

### Response Sample

```json title=""
{
  "username": "john Lee"
}
```
