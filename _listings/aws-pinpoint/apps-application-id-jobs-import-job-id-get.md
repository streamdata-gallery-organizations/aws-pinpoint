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
  /apps/application-id/jobs/import/{job-id}:
    get:
      summary: Import Job Instance
      description: Use the GET method to request information about an import job
      operationId: importJobInstance
      parameters:
      - in: path
        name: job-id
        description: The job id
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - import job
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