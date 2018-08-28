---
swagger: "2.0"
x-collection-name: Alpha Vantage
x-complete: 0
info:
  title: Alpha Vantage Sector Performance
  description: This API returns the realtime and historical sector performances calculated
    from S&P500 incumbents.
  version: 1.0.0
host: www.alphavantage.co
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /query?function=SECTOR:
    get:
      summary: Sector Performance
      description: This API returns the realtime and historical sector performances
        calculated from S&P500 incumbents.
      operationId: getSectorPerformance
      x-api-path-slug: queryfunctionsector-get
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Sector
      - Performance
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