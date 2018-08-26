---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli Get a List of Collisions for a Device
  description: Get a list of collisions for a device.
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
  /devices/cf217c2d-df3c-41f7-b610-8bc3e11b4b79/vehicles:
    get:
      summary: List a Device's Vehicles
      description: List a device's vehicles.
      operationId: DevicesCf217c2dDf3c41f7B6108bc3e11b4b79VehiclesGet
      x-api-path-slug: devicescf217c2ddf3c41f7b6108bc3e11b4b79vehicles-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Devices
      - Vehicles
  /rules/b7ad3604-c795-46af-9d5f-71be30ed4143:
    get:
      summary: Get a Specific Rule
      description: Get a specific rule.
      operationId: RulesB7ad3604C79546af9d5f71be30ed4143Get
      x-api-path-slug: rulesb7ad3604c79546af9d5f71be30ed4143-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Specific
      - Rule
  /devices/7eac0d62-854f-41c1-a5b2-ba13c460058a/collisions:
    get:
      summary: Get a List of Collisions for a Device
      description: Get a list of collisions for a device.
      operationId: Devices7eac0d62854f41c1A5b2Ba13c460058aCollisionsGet
      x-api-path-slug: devices7eac0d62854f41c1a5b2ba13c460058acollisions-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Collisionsa
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