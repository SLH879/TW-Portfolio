
# Retrieve a Watch

## Overview

Retrieve an individual watch record using its
unique watch identifier.

## Endpoint

`GET /watches/{watchId}`

## Path Parameters

| Parameter | Type | Required | Description |
|---|---|---|---|
| watchId | Integer | Yes | Unique watch ID |

## Example Request

GET /watches/101

## Successful Response

HTTP status: 200 OK

```json
{
  "id": 101,
  "brand": "Grand Seiko",
  "reference": "SBGP017",
  "status": "sold"
}
```

## Error Response

HTTP status: 404 Not Found

Returned when the requested watch ID does
not exist.

## Notes

This endpoint is currently a documented API
design. Examples are illustrative and have
not been tested against a live service.