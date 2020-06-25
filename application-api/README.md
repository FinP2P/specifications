## Overview
This specification intended to provide a standard specification for an open ecosystem of applications and services for financial institutions to choose from and work with on top of the finp2p network.
They expose the functionality of the network in a simple way, and provide many common digital securities features out of the box, without the need to develop complex blockchain code.

The Application API is specified in the [OpenAPI 3.0 format](https://www.openapis.org).
Requests and responses can be crafted with auto-generated code using
[Swagger Codegen](https://swagger.io/tools/swagger-codegen) or
[OpenAPI Generator](https://openapi-generator.tech), are human-readable
(easy to debug and understand), and can be used in servers and browsers.


[*The transactional API*][application_openapi_spec] conforms to REST. It has predictable, resource-oriented URLs, and it uses HTTP response codes to indicate API errors. JSON is returned by all API responses, including errors.

Use the [*Documentation style visualization*][application_openapi_spec_viewer] for a human readable version.


[application_openapi_spec]: ./api.yaml
[application_openapi_spec_viewer]: https://editor.swagger.io/?url=https%3A%2F%2Fraw.githubusercontent.com%2FFinP2P%2Fspecifications%2Fmaster%2Fapplication-api%2Fapi.yaml
