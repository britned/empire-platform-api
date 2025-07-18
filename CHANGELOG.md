## [7.0.0](https://github.com/britned/empire-platform-api/compare/v6.1.0...v7.0.0) (2025-07-18)


### Features

* **common:** add general bad request error code
* **finance-information:** add error codes for updateFinanceInformation
* **finance:** add invoice type to InvoiceDetails
* **finance:** align path prefix and operation ids
* **finance:** remove required from fields in invoice group
* **profile:** add manage api keys permission
* **user:** add senior admin help desk role

## [6.1.0](https://github.com/britned/empire-platform-api/compare/v6.0.5...v6.1.0) (2025-05-06)


### Features

* **organisations:** participate in gopacs flag for participant

### [6.0.5](https://github.com/britned/empire-platform-api/compare/v6.0.4...v6.0.5) (2025-03-28)

> No changes affecting Participants.

### [6.0.4](https://github.com/britned/empire-platform-api/compare/v6.0.3...v6.0.4) (2025-03-25)


### Bug Fixes

* **buy-now-offers:** add response for purchasing a buy now offer


### [6.0.3](https://github.com/britned/empire-platform-api/compare/v6.0.2...v6.0.3) (2025-03-19)

> No changes affecting Participants.

### [6.0.2](https://github.com/britned/empire-platform-api/compare/v6.0.1...v6.0.2) (2025-03-05)


### Bug Fixes

* allow phone numbers to be at most 20 digits long after plus sign


### Documentation

* publish getBuyNowOfferPurchaseDetails endpoint to the public

### [6.0.1](https://github.com/britned/empire-platform-api/compare/v6.0.0...v6.0.1) (2025-02-24)


### Bug Fixes

* remove operations from public-api-docs that are no longer accessible via API Keys

## [6.0.0](https://github.com/britned/empire-platform-api/compare/v5.0.3...v6.0.0) (2025-02-21)


### ⚠ BREAKING CHANGES

* **buy-now-offers:** change endpoints and schemas to Buy Now 2.0
* **profile:** user preferences extended with browser notification
* **bidding-configuration:** add day ahead and intraday bidding configuration
* **profile:** add timescale preferences to profile and preference endpoints
* **public-nominations:** typo in required field name

### Features

* **auctions:** add buy now offers to getAuctionOverview endpoint
* **auctions:** add getAuctionOverview endpoint
* **auctions:** update auction status filter and DayAheadAuction
* **bidding-configuration:** add day ahead and intraday bidding configuration
* **buy-now-offers:** change endpoints and schemas to Buy Now 2.0
* change openapi version to 3.1.1
* **profile:** add timescale preferences to profile and preference endpoints
* **profile:** user preferences extended with browser notification
* **webhooks:** add auction result webhook event types
* **webhooks:** add get and update webhooks endpoints
* **webhooks:** add get webhook history endpoint
* **webhooks:** add webhook requests
* **webhooks:** add webhook skeletons
* **webhooks:** create testWebhook endpoint
* **webhooks:** rename token to signing secret


### Bug Fixes

* **profile:** extend email notification options for unplanned outages and curtailment
* **profile:** refactor notification preference schemas
* **public-nominations:** typo in required field name
* **reporting:** missing explicit array definitions
* **webhooks:** plural responseHeaders and add errorMessage
* **webhooks:** various fixes around webhook endpoints


### Build

* move existing python targets to python-legacy with oasg v16.0.0
* re-add python targets with oasg v16.2.0

### [5.0.3](https://github.com/britned/empire-platform-api/compare/v5.0.2...v5.0.3) (2024-12-18)

> No changes affecting Participants.

### [5.0.2](https://github.com/britned/empire-platform-api/compare/v5.0.1...v5.0.2) (2024-11-07)

> No changes affecting Participants.

### [5.0.1](https://github.com/britned/empire-platform-api/compare/v5.0.0...v5.0.1) (2024-10-31)


### Bug Fixes

* **finance:** optional product types and multiple timescales in getFinanceSettlementPerSource

## [5.0.0](https://github.com/britned/empire-platform-api/compare/v4.0.0...v5.0.0) (2024-10-21)


### ⚠ BREAKING CHANGES

* **finance:** change getFinanceInvoices response to groups
* **participant-overview:** extend participant overview data
* **finance:** support optional product types and multiple timescales in getFinanceSettlementPerDay
* **secondary-market:** allow secondary market returns list for multiple participants

### Features

* **allocated-auctions:** add bidding period filter to allocated auction endpoints
* **auctions, public-auctions:** add next / previous auction properties to auction details
* **buy-now-offers:** add getBuyNowOffer endpoint
* **finance, reporting:** add getInvoiceGroupPdfs endpoint
* **finance:** add downloadAllFinanceInvoiceGroupPdfs endpoint
* **finance:** add groupId to getFinanceInvoice response
* **finance:** change getFinanceInvoices response to groups
* **finance:** support optional product types and multiple timescales in getFinanceSettlementPerDay
* **participant-overview:** extend participant overview data
* **reporting:** getAuctionsBidsReport
* **secondary-market:** allow secondary market returns list for multiple participants


### Bug Fixes

* **buy-now-offers:** make getBuyNowOffer endpoint plural
* **finance:** getFinanceInvoices make due date optional
* **secondary-market:** add nomination gate close to secondary market transfer request options
* **secondary-market:** make getSecondaryMarketReturnRequests ParticipantIds mandatory


### Styling

* enforce alphabetical ordering for certain enums

## [4.0.0](https://github.com/britned/empire-platform-api/compare/v3.0.10...v4.0.0) (2024-08-13)


### ⚠ BREAKING CHANGES

* **auctions:** rename externalId field to bidTag

### Features

* **auctions:** add offeredCapacityManuallyUpdated flag to IntraDayAuction and DayAheadAuction
* **auctions:** rename externalId field to bidTag
* **reporting:** add getFinanceAuctionResultsSettlementPerParticipantReport endpoint
* **reporting:** add getFinanceBoughtOrSoldCapacityReport endpoint

### [3.0.10](https://github.com/britned/empire-platform-api/compare/v3.0.9...v3.0.10) (2024-05-23)


### Features

* **nomination:** enable querying bpp nominations for providers

### [3.0.9](https://github.com/britned/empire-platform-api/compare/v3.0.8...v3.0.9) (2024-05-23)

> No changes affecting Participants.

### [3.0.8](https://github.com/britned/empire-platform-api/compare/v3.0.7...v3.0.8) (2024-04-15)

> No changes affecting Participants.

### [3.0.7](https://github.com/britned/empire-platform-api/compare/v3.0.6...v3.0.7) (2024-04-15)

> No changes affecting Participants.

### [3.0.6](https://github.com/britned/empire-platform-api/compare/v3.0.5...v3.0.6) (2024-03-11)

> No changes affecting Participants.

### [3.0.5](https://github.com/britned/empire-platform-api/compare/v3.0.4...v3.0.5) (2024-03-08)

> No changes affecting Participants.

### [3.0.4](https://github.com/britned/empire-platform-api/compare/v3.0.3...v3.0.4) (2024-03-08)

> No changes affecting Participants.

### [3.0.3](https://github.com/britned/empire-platform-api/compare/v3.0.2...v3.0.3) (2024-03-08)

> No changes affecting Participants.

### [3.0.2](https://github.com/britned/empire-platform-api/compare/v3.0.1...v3.0.2) (2024-03-08)

> No changes affecting Participants.

### [3.0.1](https://github.com/britned/empire-platform-api/compare/v3.0.0...v3.0.1) (2024-03-01)

> No changes affecting Participants.

## [3.0.0](https://github.com/britned/empire-platform-api/compare/v2.0.0...v3.0.0) (2024-02-16)


### ⚠ BREAKING CHANGES

* **reporting:** auction allocation results can be queried using a displayId
* **auctions:** uniform filtering for enum arrays both internal/public list and results

### Features

* **auctions:** uniform filtering for enum arrays both internal/public list and results
* **reporting:** auction allocation results can be queried using a displayId

## [2.0.0](https://github.com/britned/empire-platform-api/compare/v1.1.0...v2.0.0) (2024-01-16)


### ⚠ BREAKING CHANGES

* **auctions:** remove access for Participants to others' DA/ID allocation results
* **reporting:** remove access to getFinanceAuctionResultsSettlementReport for Participants

### Features

* **auctions:** allow price to be set as 0 for LT bids
* **auctions:** remove access for Participants to others' DA/ID allocation results
* **reporting:** add access to getFinanceCreditCoverReport for Participants
* **reporting:** add access to getFinanceCreditLimitReport for Participants
* **reporting:** add uiosi hourly finance report
* **reporting:** remove access to getFinanceAuctionResultsSettlementReport for Participants



## [1.1.0](https://github.com/britned/empire-platform-api/compare/v1.0.5...v1.1.0) (2023-10-18)


### Features

* **allocated-auctions:** add authenticated version of public endpoints
* **allocated-auctions:** filter for participant results
* **auctions:** add optional externalId for bids
* **audit-logs:** add status based filtering to get audit logs
* **audit-logs:** change get audit logs to use cursor based pagination
* **nominations:** add new pre-nomination options endpoint for aggregated nominations
* **reporting:** enable "all orgs" option for audit log and credit limit reports
* **users:** allow resend and revoke invites with user management permissions


### Bug Fixes

* **auctions, public-auctions:** use explicit list of statuses available for auction schedules
* **python:** datetime formatting in query params, remove dead validation code


### Refactoring

* **public-allocated-auctions:** use common schemas


### [1.0.5](https://github.com/britned/empire-platform-api/compare/v1.0.4...v1.0.5) (2023-09-27)

> No changes affecting Participants.

### [1.0.4](https://github.com/britned/empire-platform-api/compare/v1.0.3...v1.0.4) (2023-09-25)

> No changes affecting Participants.

### [1.0.3](https://github.com/britned/empire-platform-api/compare/v1.0.2...v1.0.3) (2023-09-21)

> No changes affecting Participants.

### [1.0.2](https://github.com/britned/empire-platform-api/compare/v1.0.1...v1.0.2) (2023-09-13)

> No changes affecting Participants.

### [1.0.1](https://github.com/britned/empire-platform-api/compare/v1.0.0...v1.0.1) (2023-09-11)

> No changes affecting Participants.

## [1.0.0](https://github.com/britned/empire-platform-api/compare/v0.179.13...v1.0.0) (2023-08-29)


### Documentation

* update API info and server URLs

### [0.179.13](https://github.com/britned/empire-platform-api/compare/v0.179.12...v0.179.13) (2023-08-22)


### Bug Fixes

* **reporting:** make invoice period required in getFinanceBillingReport

### [0.179.12](https://github.com/britned/empire-platform-api/compare/v0.179.11...v0.179.12) (2023-08-21)


### Bug Fixes

* **reporting:** add participant ID to getAuctionAllocationResultsReport

### [0.179.11](https://github.com/britned/empire-platform-api/compare/v0.179.10...v0.179.11) (2023-08-21)


### Features

* **auctions:** add report for fetching auction results in XML

### [0.179.10](https://github.com/britned/empire-platform-api/compare/v0.179.9...v0.179.10) (2023-08-21)

> No changes affecting Participants.

### [0.179.9](https://github.com/britned/empire-platform-api/compare/v0.179.8...v0.179.9) (2023-08-18)


### Bug Fixes

* **dashboard:** remove timescale filter from netted nominations

### [0.179.8](https://github.com/britned/empire-platform-api/compare/v0.179.7...v0.179.8) (2023-08-18)


### Bug Fixes

* **auctions, public-auctions:** remove unused biddingResults from LT details
* **auctions:** add totalRequested and totalAllocated capacity for LT results

### [0.179.7](https://github.com/britned/empire-platform-api/compare/v0.179.6...v0.179.7) (2023-08-18)


### Bug Fixes

* **reporting:** make biddingPeriod optional for getAuctionsScheduleReport
* **reporting:** make validityPeriod optional for getTrsAndNominationsBuyNowReport
* **reporting:** validating either deliveryPeriod or invoicePeriod for getFinanceBillingReport

### [0.179.6](https://github.com/britned/empire-platform-api/compare/v0.179.5...v0.179.6) (2023-08-18)

> No changes affecting Participants.

### [0.179.5](https://github.com/britned/empire-platform-api/compare/v0.179.4...v0.179.5) (2023-08-18)

> No changes affecting Participants.

### [0.179.4](https://github.com/britned/empire-platform-api/compare/v0.179.3...v0.179.4) (2023-08-15)


### Bug Fixes

* **auctions:** use the right permission for fetching DA/ID bids

### [0.179.3](https://github.com/britned/empire-platform-api/compare/v0.179.2...v0.179.3) (2023-08-15)


### Bug Fixes

* typo in plural BorderDirections parameter name

### [0.179.2](https://github.com/britned/empire-platform-api/compare/v0.179.1...v0.179.2) (2023-08-14)


### Documentation

* publish documentation for finance-related reports accessible by participants

### [0.179.1](https://github.com/britned/empire-platform-api/compare/v0.179.0...v0.179.1) (2023-08-14)

> No changes affecting Participants.
