# Yandex Scooter — Comprehensive QA Project

Testing the order web interface, form validation, mobile notifications, and API.

**Workbook:** [yandex-samokat-web.xlsx](./yandex-samokat-web.xlsx)

## Contents

- `Задание 1 чек-лист` and `Задание 1 данные валидации` — web UI and input validation.
- `Задание 1 баги вне тестовой док` — additional defects.
- `Задание 2 тест-кейсы` — mobile notifications and offline behavior.
- `Задание 3 чек-лист API` — API requests and responses.
- `Баг-репорты` — defect reports.

## Test Analysis Techniques

- Separation of coverage into web UI, field validation, mobile scenarios, and API operations.
- Analysis of order states, notification timing, and behavior without a network connection.

## Test Design Techniques

- Equivalence partitioning and boundary value analysis for field validation.
- Positive and negative scenarios for orders, notifications, and API calls.
- Time-based checks around the 21:59 notification threshold.
- Cross-browser UI and functional checks.

## Tools and Environment

- Yandex Browser and Google Chrome — web UI testing.
- Android Studio emulator — mobile scenarios.
- Swagger — API documentation.
- Postman — API requests and response checks.
- PostgreSQL — checking API results.
- XLSX workbook — test data, checklists, test cases, and defect reports.
