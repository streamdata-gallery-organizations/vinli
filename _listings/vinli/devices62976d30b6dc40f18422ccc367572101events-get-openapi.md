---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli Get All Events for a Device
  description: Get all events for a device.
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/62976d30-b6dc-40f1-8422-ccc367572101/events:
    get:
      summary: Get All Events for a Device
      description: Get all events for a device.
      operationId: Devices62976d30B6dc40f18422Ccc367572101EventsGet
      x-api-path-slug: devices62976d30b6dc40f18422ccc367572101events-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Eventsa
      - Device
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