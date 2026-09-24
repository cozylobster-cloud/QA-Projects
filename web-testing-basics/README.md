# Web UI and Functional Testing Projects

Four QA projects covering a feedback form, Kittygram login, subscription plan selection, and the Yandex Routes web application. Each workbook contains its own testing artifacts and results.

## Project Files

| Workbook | Scope | Artifacts |
| --- | --- | --- |
| [feedback-form-ui-and-logic-testing.xlsx](./feedback-form-ui-and-logic-testing.xlsx) | Feedback form UI, validation, and message submission | Requirements decomposition, equivalence classes, boundary values, test cases, bug reports |
| [login-form-testing.xlsx](./login-form-testing.xlsx) | Login UI and authentication | Requirements decomposition, equivalence classes, boundary values, test cases, bug reports |
| [tariff-plan-selection-form-testing.xlsx](./tariff-plan-selection-form-testing.xlsx) | Multistep plan selection and pricing | UI and logic decomposition, test design, checklists, bug reports |
| [yandex-routes-web-app-testing.xlsx](./yandex-routes-web-app-testing.xlsx) | Departure time fields, mode and transport controls | Test analysis, equivalence classes, boundary values, test cases, bug reports |

## Test Analysis Techniques

- **Feedback form:** decomposed the UI into page and form elements and analyzed field rules, submit button states, and submission outcomes.
- **Kittygram login:** decomposed the login page and analyzed successful and unsuccessful authentication paths, credentials, and error behavior.
- **Subscription plans:** decomposed the four form steps and identified personal data fields, plans, billing periods, optional features, and pricing rules.
- **Yandex Routes:** decomposed hour and minute input rules, empty field behavior, and mode and transport switch states.

## Test Design Techniques

- **Equivalence partitioning:** used valid and invalid input classes across the four projects, including empty fields, credential variations, text formats, and numeric inputs.
- **Boundary value analysis:** checked field lengths in the form projects and time input limits in Yandex Routes, including hour values around 0, 9/10, and 23/24.
- **Positive and negative scenarios:** covered form submission, login, transitions between subscription steps, pricing selections, and time field validation.
- **UI checks:** compared form elements with documented requirements; the subscription plan project also contains separate UI and functional checklists.

## Tools and Environment

- **Subscription plans:** Google Chrome, Yandex Browser, and Firefox on Windows 10.
- **Yandex Routes:** Yandex Browser.
- **Feedback form and login:** the workbooks do not identify a specific browser or testing application.
- **Documentation:** XLSX workbooks containing analysis, test data, checklists or test cases, and bug reports.
