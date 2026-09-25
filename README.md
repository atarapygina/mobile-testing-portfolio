# OLX Mobile QA Testing

Manual QA testing portfolio case demonstrating functional, exploratory, UI/UX, navigation, data validation, negative, and stability testing of the OLX mobile application.

## Test Environment

* **Application:** OLX mobile app
* **Device:** iPhone 12
* **OS:** iOS 18.1.1
* **App version:** olx 4.154.04
* **Testing type:** Manual / Exploratory
* **Testing areas:** Functional, UI/UX, navigation, data validation, negative testing, stability

## Testing Scope

The testing focused on several core user flows:

* Authentication and logout
* Search and search history
* Ad creation and editing
* Price input and validation
* OLX Delivery settings
* Messages and navigation
* Application stability
* UI/UX consistency

## Key Findings

During exploratory testing, I identified 7 issues with different levels of impact:

| ID      | Issue                                                                                 | Type                       | Severity |
| ------- | ------------------------------------------------------------------------------------- | -------------------------- | -------- |
| BUG-001 | Application crashes when entering a 17-digit price                                    | Stability / Validation     | High     |
| BUG-002 | Incorrect price is displayed after the buyer suggests a price of 19.99                | Data accuracy              | Medium   |
| BUG-003 | Previous search data remains visible after logout                                     | Privacy / Data persistence | Medium   |
| BUG-004 | OLX Delivery is automatically enabled after editing an ad                             | UX / Business logic        | Medium   |
| BUG-005 | "Cancel" redirects to an empty ad creation page after the ad has already been created | Navigation / UX            | Medium   |
| BUG-006 | Logout confirmation flow contains confusing UI/text behavior                          | UI/UX                      | Low      |
| BUG-007 | Messages does not consistently open the tab containing the new message                | Navigation / UX            | Low      |

## Bug Reports

* [BUG-001: App crash after 17-digit price input in Price field](https://github.com/atarapygina/mobile-testing-portfolio/issues/1)
* [BUG-002: Price calculation discrepancy](https://github.com/atarapygina/mobile-testing-portfolio/issues/2)
* [BUG-003: Previous search data remains visible after logout](https://github.com/atarapygina/mobile-testing-portfolio/issues/3)
* [BUG-004: OLX Delivery enabled after editing an ad](./bug-reports/BUG-004.md)
* [BUG-005: Incorrect navigation after cancelling ad creation](./bug-reports/BUG-005.md)
* [BUG-006: Confusing logout confirmation flow](./bug-reports/BUG-006.md)
* [BUG-007: Messages tab does not consistently open on new message](./bug-reports/BUG-007.md)

## Testing Approach

I used exploratory testing to identify unexpected behavior beyond the happy path, with particular attention to:

* Boundary and negative scenarios
* State transitions
* Data persistence
* Navigation behavior
* Input validation
* User experience
* Application stability

## Portfolio Video

[Mobile QA Testing — OLX iOS](YOUTUBE-LINK-Will-BE-HERE)

## About

QA Engineer with 6+ years of experience in manual web, backend, API, and mobile testing.

Experienced with functional, regression, exploratory, API, UI, integration, and end-to-end testing, as well as Postman, SQL, DevTools, BrowserStack, Charles/Fiddler, Jira, TestRail, and AWS logs.
