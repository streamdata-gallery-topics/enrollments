---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Create an Enrollment
  description: Create an Enrollment
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cps/v2/enrollments:
    post:
      summary: Create an Enrollment
      description: Create an Enrollment
      operationId: cpsv2enrollmentscontractid
      x-api-path-slug: cpsv2enrollments-post
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract under which to create a new
          enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Contract
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