swagger: "2.0"
x-collection-name: PredictHQ
x-complete: 1
info:
  title: PredictHQ API
  description: todo-add-description
  version: 1.0.0
host: api.predicthq.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/events/calendar/:
    get:
      summary: Retrieve Events Calendar
      description: |-
        This endpoint accepts the same parameters as the ones described in Retrieve All Events and can be used to get a calendar view of all matching events that are available to your account.

        Each day in the calendar contains aggregate counts of all _active_ events for that day.
      operationId: V1EventsCalendarGet
      x-api-path-slug: v1eventscalendar-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Calendar