---
swagger: "2.0"
x-collection-name: Vinli
x-complete: 0
info:
  title: Vinli Create a Dummy Device
  description: Create a dummy device.
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
  /odometer_triggers/ce8f9a53-906a-4d39-b06a-d466d29a13f1:
    get:
      summary: Get an Odometer Trigger
      description: Get an odometer trigger.
      operationId: OdometerTriggersCe8f9a53906a4d39B06aD466d29a13f1Get
      x-api-path-slug: odometer-triggersce8f9a53906a4d39b06ad466d29a13f1-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Odometer
      - Trigger
    delete:
      summary: Delete an Odometer Trigger
      description: Delete an odometer trigger.
      operationId: OdometerTriggersCe8f9a53906a4d39B06aD466d29a13f1Delete
      x-api-path-slug: odometer-triggersce8f9a53906a4d39b06ad466d29a13f1-delete
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Odometer
      - Trigger
  /events/1caa8fff-c9be-4506-bcb8-38371c25aa14:
    get:
      summary: Get a Specific Event
      description: Get a specific event.
      operationId: Events1caa8fffC9be4506Bcb838371c25aa14Get
      x-api-path-slug: events1caa8fffc9be4506bcb838371c25aa14-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Specific
      - Event
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometer_triggers:
    get:
      summary: List all Odometer Triggers for a Vehicle
      description: List all odometer triggers for a vehicle.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometerTriggersGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30odometer-triggers-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Odometer
      - Triggersa
      - Vehicle
    post:
      summary: Create an Odometer Trigger
      description: Create an odometer trigger.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometerTriggersPost
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30odometer-triggers-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Odometer
      - Trigger
  /vehicles/aa44769b-3c0a-4662-9bad-25481cf5198f:
    get:
      summary: Get Vehicle Details
      description: Get vehicle details.
      operationId: VehiclesAa44769b3c0a46629bad25481cf5198fGet
      x-api-path-slug: vehiclesaa44769b3c0a46629bad25481cf5198f-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Vehicle
      - Details
  /devices/62976d30-b6dc-40f1-8422-ccc367572101/snapshots:
    get:
      summary: Telemetry Snapshots
      description: Telemetry snapshots.
      operationId: Devices62976d30B6dc40f18422Ccc367572101SnapshotsGet
      x-api-path-slug: devices62976d30b6dc40f18422ccc367572101snapshots-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: fields
      responses:
        200:
          description: OK
      tags:
      - Telemetry
      - Snapshots
  /devices/62976d30-b6dc-40f1-8422-ccc367572101/subscriptions:
    get:
      summary: Get all Subscriptions for a Device
      description: Get all subscriptions for a device.
      operationId: Devices62976d30B6dc40f18422Ccc367572101SubscriptionsGet
      x-api-path-slug: devices62976d30b6dc40f18422ccc367572101subscriptions-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Subscriptionsa
      - Device
    post:
      summary: Update a Subscription
      description: Update a subscription.
      operationId: Devices62976d30B6dc40f18422Ccc367572101SubscriptionsPost2
      x-api-path-slug: devices62976d30b6dc40f18422ccc367572101subscriptions-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Subscription
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/trips:
    get:
      summary: List All of a Vehicle's Trips
      description: List all of a vehicle's trips.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30TripsGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30trips-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Of
      - Vehicles
      - Trips
  /devices:
    get:
      summary: List all devices
      description: List all devices.
      operationId: DevicesGet
      x-api-path-slug: devices-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Devices
    post:
      summary: Register a Device
      description: Register a device.
      operationId: DevicesPost
      x-api-path-slug: devices-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Register
      - Device
  /vehicles/428bc621-16e7-489b-a02a-eb98526d01ef/collisions:
    get:
      summary: Get a List of Collisions for a Vehicle
      description: Get a list of collisions for a vehicle.
      operationId: Vehicles428bc62116e7489bA02aEb98526d01efCollisionsGet
      x-api-path-slug: vehicles428bc62116e7489ba02aeb98526d01efcollisions-get
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
      - Vehicle
  /collisions/e43ff87d-bb58-42da-998e-d7f10a3f7a64:
    get:
      summary: Get a specific Collision
      description: Get a specific collision.
      operationId: CollisionsE43ff87dBb5842da998eD7f10a3f7a64Get
      x-api-path-slug: collisionse43ff87dbb5842da998ed7f10a3f7a64-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Specific
      - Collision
  /codes:
    get:
      summary: Get Info about a DTC
      description: Get info about a dtc.
      operationId: CodesGet
      x-api-path-slug: codes-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: number
      responses:
        200:
          description: OK
      tags:
      - Info
      - About
      - DTC
  /trips/report_card:
    post:
      summary: Report Card  for a Trip
      description: Report card  for a trip.
      operationId: TripsReportCardPost
      x-api-path-slug: tripsreport-card-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Report
      - Card
      - Trip
  /devices/821374c0-d6d8-11e3-9c1a-0800200c9a66/vehicles/_latest:
    get:
      summary: Get Device's Latest Vehicle
      description: Get device's latest vehicle.
      operationId: Devices821374c0D6d811e39c1a0800200c9a66VehiclesLatestGet
      x-api-path-slug: devices821374c0d6d811e39c1a0800200c9a66vehicles-latest-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Devices
      - Latest
      - Vehicle
  /messages/ade8e85c-a1aa-4373-8c6e-e37e87762f29:
    get:
      summary: Get a Specific Telemety Message
      description: Get a specific telemety message.
      operationId: MessagesAde8e85cA1aa43738c6eE37e87762f29Get
      x-api-path-slug: messagesade8e85ca1aa43738c6ee37e87762f29-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Specific
      - Telemety
      - Message
  /devices/62976d30-b6dc-40f1-8422-ccc367572101/locations:
    get:
      summary: Locations Request
      description: Locations request.
      operationId: Devices62976d30B6dc40f18422Ccc367572101LocationsGet
      x-api-path-slug: devices62976d30b6dc40f18422ccc367572101locations-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: fields
      responses:
        200:
          description: OK
      tags:
      - Locations
      - Request
  /vehicles/8480c5b7-6f3e-40b3-a78e-3555617d44b0/report_cards:
    get:
      summary: Report Cards for a Vehicle
      description: Report cards for a vehicle.
      operationId: Vehicles8480c5b76f3e40b3A78e3555617d44b0ReportCardsGet
      x-api-path-slug: vehicles8480c5b76f3e40b3a78e3555617d44b0report-cards-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - Report
      - Cardsa
      - Vehicle
  /dummies/01e668ba-6967-4536-9f72-cc28ff18d7b6/runs:
    post:
      summary: Create a Dummy Run
      description: Create a dummy run.
      operationId: Dummies01e668ba696745369f72Cc28ff18d7b6RunsPost
      x-api-path-slug: dummies01e668ba696745369f72cc28ff18d7b6runs-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Dummy
      - Run
  /dummies/01e668ba-6967-4536-9f72-cc28ff18d7b6/runs/_current:
    get:
      summary: Get Current Run
      description: Get current run.
      operationId: Dummies01e668ba696745369f72Cc28ff18d7b6RunsCurrentGet
      x-api-path-slug: dummies01e668ba696745369f72cc28ff18d7b6runs-current-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Current
      - Run
    delete:
      summary: Delete a Run
      description: Delete a run.
      operationId: Dummies01e668ba696745369f72Cc28ff18d7b6RunsCurrentDelete
      x-api-path-slug: dummies01e668ba696745369f72cc28ff18d7b6runs-current-delete
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Run
  /vehicles/9aa35c64-b046-43cc-9cd8-4c353a6d0b30/odometers:
    get:
      summary: List All Odometer Reports for a Vehicle
      description: List all odometer reports for a vehicle.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometersGet
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30odometers-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Odometer
      - Reportsa
      - Vehicle
    post:
      summary: Create an Odometer Report
      description: Create an odometer report.
      operationId: Vehicles9aa35c64B04643cc9cd84c353a6d0b30OdometersPost
      x-api-path-slug: vehicles9aa35c64b04643cc9cd84c353a6d0b30odometers-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Odometer
      - Report
  /dummies:
    get:
      summary: List Dummy Devices
      description: List dummy devices.
      operationId: DummiesGet
      x-api-path-slug: dummies-get
      parameters:
      - in: header
        name: Accept
      responses:
        200:
          description: OK
      tags:
      - List
      - Dummy
      - Devices
    post:
      summary: Create a Dummy Device
      description: Create a dummy device.
      operationId: DummiesPost
      x-api-path-slug: dummies-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Dummy
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