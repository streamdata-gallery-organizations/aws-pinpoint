---
swagger: "2.0"
info:
  title: AWS Pinpoint API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /apps/application-id/endpoints:
    put:
      summary: Endpoints List
      description: Use the PUT method to update your endpoints
      operationId: updateEndpointsList
      parameters:
      - in: query
        name: accept
        description: "Specify the media type you will accept as a response:  application/json
          \u2013 A JSON response body"
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - endpoint
definitions: []
x-collection-name: AWS Pinpoint
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