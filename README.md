# f5-irules-jwt

This are proof of concept iRules to create, sign, decode and validate a JWT. It supports only JWT's signed with RS256.

It is not designed for production usage, especially there are more checks required to comply with https://datatracker.ietf.org/doc/html/rfc7519#section-7.2.

| iRule | Description |
| -- | -- |
| jwt-sign | Creates and signs a JWT. |
| jwt-validate | Decodes and validates a JWT. |
| jwt-view | Decodes the JWT in the browser. |
