# API Specification

**API Name:**\
**Owner:**\
**Version:** v1\
**Status:** Draft / Review / Approved

## 1. Purpose

What does this API provide?

## 2. Base URL

``` text
https://api.example.com/v1
```

## 3. Authentication

Authentication method:

Authorization requirements:

## 4. Endpoint

### \[METHOD\] /resource

**Purpose:**

**Request Headers:**

``` text
Authorization: Bearer <token>
Content-Type: application/json
```

**Request:**

``` json
{
  "example": "value"
}
```

**Response:**

``` json
{
  "id": "123",
  "status": "active"
}
```

**Status Codes:**

  Code   Meaning
  ------ -----------------
  200    Success
  400    Invalid request
  401    Unauthorized
  403    Forbidden
  404    Not found
  409    Conflict
  429    Rate limited
  500    Server error

## 5. Validation Rules

-   
-   

## 6. Business Rules

-   
-   

## 7. Idempotency

Required: Yes / No

If required, explain the idempotency key and behavior.

## 8. Pagination

Default:

Maximum:

Response metadata:

## 9. Rate Limiting

Limit:

Window:

Behavior when exceeded:

## 10. Error Format

``` json
{
  "code": "ERROR_CODE",
  "message": "Human readable message",
  "details": []
}
```

## 11. Security

-   Authentication
-   Authorization
-   Input validation
-   Sensitive data handling
-   Audit logging

## 12. Versioning

Version strategy:

## 13. Related APIs

-   
