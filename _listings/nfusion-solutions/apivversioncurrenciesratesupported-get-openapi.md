---
swagger: "2.0"
x-collection-name: nFusion Solutions
x-complete: 0
info:
  title: nFusion API Get list of currencies supported by the rate endpoint
  description: "Any of the currencies in this list can be paired with any other currency
    in this list when supplied to the Rate endpoint.\r\nFor example: USD/CAD,CAD/USD,USD/EUR,EUR/CAD"
  contact:
    name: nFusion Solutions
    url: https://nfusionsolutions.com/contact
    email: support@nfusionsolutions.com
  version: 1.0.0
host: api.nfusionsolutions.biz
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v{version}/Currencies/rate/supported:
    get:
      summary: Get list of currencies supported by the rate endpoint
      description: "Any of the currencies in this list can be paired with any other
        currency in this list when supplied to the Rate endpoint.\r\nFor example:
        USD/CAD,CAD/USD,USD/EUR,EUR/CAD"
      operationId: ApiV{versionCurrenciesRateSupportedGet
      x-api-path-slug: apivversioncurrenciesratesupported-get
      parameters:
      - in: query
        name: format
        description: to override content negotiation specify a value of json or xml
      - in: query
        name: token
        description: auth token
      - in: path
        name: version
        description: The requested API version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Currencies
      - Supported
      - By
      - Rate
      - Endpoint
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---