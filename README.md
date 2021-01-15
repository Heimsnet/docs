---
description: >-
  This is the public API for Heimsnet clients. This API is the same one that our
  billing panel communicates with.
---

# Home

### Authentication

All API versions implement bearer tokens for authentication. JWT's are only used on the [billing panel](https://www.heimsnet.eu/login) itself. To acquire a bearer token you can create one via the [billing panel](https://www.heimsnet.eu/login).

### Communicating with the API

The API's base URI is `https://api.heimsnet.eu/` with the API version being in between the base URI and any endpoint. An example would be `https://api.heimsnet.eu/v1/endpoint-name`

### API versions

The following API versions exist and can be used:

* [v1 - In development](v1.md)

