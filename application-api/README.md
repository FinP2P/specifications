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

[*The query API*][application_graphql_schema] conform to GraphQL, as such it offers significantly more flexibility for the application development. The ability to define precisely the data you want—and only the data you want—is a powerful advantage over the REST. GraphQL lets you replace multiple REST requests with a single call to fetch the data you specify.

Use the [*Schema Explorer*][application_graphql_schema_viewer] to explore the query API schema. 

[application_openapi_spec]: ./api.yaml
[application_openapi_spec_viewer]: https://editor.swagger.io/?url=https%3A%2F%2Fraw.githubusercontent.com%2FFinP2P%2Fspecifications%2Fmaster%2Fapplication-api%2Fapi.yaml
[application_graphql_schema]: ./schema.graphql
[application_graphql_schema_viewer]: https://finp2p.github.io/graphql/index.html
