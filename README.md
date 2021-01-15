---
description: >-
  This is the public API for Heimsnet clients. This API is the same one that our
  billing panel communicates with.
---

# Home

### Authentication

To authenticate with the API a valid password or oAuth2 token must be presented to the authentication endpoint where it is exchanged for a temporary jwt authorization token. Alternatively permanent bearer tokens can be created in the API section of the settings page on the [billing panel](https://www.heimsnet.eu/login).

### Communicating with the API

The API's base URI is `https://api.heimsnet.eu/` with the API version being in between the base URI and any endpoint. An example would be `https://api.heimsnet.eu/v1/endpoint-name`

### API versions

The following API versions exist and can be used:

* [v1 - In development](v1.md)

