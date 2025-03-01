# Remote API

This API is used for Wings communication and is primarily for Wings, but can be accessed externally. This API is not documented so there is very little information about it.

## Access

The `Authorization` header must be present in the requests and must be prefixed with "Bearer " followed by the node's token_id, a period, then the node's token. The token can be obtained in the configuration page of a node in the admin panel, or from the [node configuration endpoint](/pterodactyl/application/nodes.md#get-nodesidconfiguration) in the application API. The `Accept` header must be set to "application/json" for requests, and the `Content-Type` must be set to "application/json" when making `POST` requests.
