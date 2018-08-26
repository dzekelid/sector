---
swagger: "2.0"
x-collection-name: Alpha Vantage
x-complete: 1
info:
  title: Alpha Vantage
  description: alpha-vantage-apis-are-grouped-into-four-categories-1-stock-time-series-data-2-physical-and-digitalcrypto-currencies-e-g--bitcoin-3-stock-technical-indicators-and-4-sector-performances--all-apis-are-realtime-the-latest-data-points-are-derived-from-the-current-trading-day--
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
---