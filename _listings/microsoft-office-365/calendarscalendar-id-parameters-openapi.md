---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Parameters Calendars Calendar
  description: Parameters calendars calendar
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Calendar:
    get:
      summary: Get Calendar
      description: Retrieve information about the default calendar by using the...
      operationId: getCalendar
      x-api-path-slug: calendar-get
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /Calendars{calendar_id}:
    get:
      summary: Get Calendars Calendar
      description: You can also retrieve information about a specific calendar ...
      operationId: getCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-get
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
    delete:
      summary: Delete Calendars Calendar
      description: Deleting a calendar is as simple as sending a DELETE request...
      operationId: deleteCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-delete
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
    patch:
      summary: Patch Calendars Calendar
      description: You can update a calendar by sending a PATCH request with a ...
      operationId: patchCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-patch
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
    parameters:
      summary: Parameters Calendars Calendar
      description: Parameters calendars calendar
      operationId: parametersCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
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