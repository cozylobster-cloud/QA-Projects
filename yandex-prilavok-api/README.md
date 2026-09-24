# Yandex Prilavok — API Testing

API testing of product kits, orders, and delivery calculation.

**Workbook:** [yandex-prilavok-api-testing.xlsx](./yandex-prilavok-api-testing.xlsx)

## Contents

- `Чек-лист API` — requests, expected responses, and execution results.
- `Баг-репорты` — defects and reproduction steps.

## Test Analysis Techniques

- Endpoint decomposition by operation and request parameter.
- Analysis of resource IDs, product quantities, kit contents, orders, and delivery calculations.
- Analysis of the response contract: HTTP status, response structure, and resulting data changes.

## Test Design Techniques

- Equivalence partitioning for valid and invalid IDs and quantities, existing and missing resources, and request bodies.
- Boundary value checks around kit size limits, including 29 and 30 items, and quantity values such as zero and negative numbers.
- Positive and negative API scenarios with checks of HTTP statuses and data state.

## Tools and Environment

- Swagger — API documentation.
- Postman — sending requests and checking responses.
- XLSX workbook — API checklist and bug reports.
