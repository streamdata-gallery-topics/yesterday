---
swagger: "2.0"
x-collection-name: Weather Underground
x-complete: 1
info:
  title: Weather Underground
  description: get-forecast-and-weather-data-with-complete-geolocation-services-global-coverage-and-more-
  version: 1.0.0
host: api.wunderground.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{key}/yesterday/q/CA/San_Francisco.json:
    get:
      summary: Get Key Yesterday Q Ca San Francisco
      description: This example will return yesterday's weather in San Francisco,
        California.
      operationId: Get_yesterday_example_
      x-api-path-slug: keyyesterdayqcasan-francisco-json-get
      parameters:
      - in: path
        name: city
        description: The city
        type: string
        format: string
      - in: path
        name: state
        description: The state
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Key
      - Yesterday
      - Q
      - CA
      - San
      - Francisco
      - Json
---