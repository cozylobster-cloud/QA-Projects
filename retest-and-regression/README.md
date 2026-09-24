# Mesto — Bug Reports and Retesting

Bug reporting and retesting for the Mesto web application. The work covers profile editing, field validation, place cards, and verification of reported fixes.

## Project Files

- [bug-reports.xlsx](./bug-reports.xlsx) — bug reports with reproduction steps, expected and actual results, severity, and environment details.
- [bug-retest.xlsx](./bug-retest.xlsx) — retest results, defect statuses, and comments.

## Test Analysis Techniques

- Analyzed expected results in bug reports to identify requirements for profile fields and place cards.
- Reviewed each defect and its reproduction steps to determine how to verify the fix.
- Identified cases where retesting was blocked by another issue.

## Test Design and Execution

- Checked individual cases involving empty inputs, field length, and interactions with profiles and place cards.
- Retested defects by repeating the documented steps and comparing the new result with the expected result.
- Recorded whether a defect was closed, reopened, or blocked.

## Tools and Environment

- Yandex Browser on macOS.
- Mesto test environment.
- XLSX workbooks for bug reporting and retest results.
