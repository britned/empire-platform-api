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

## [0.179.0](https://github.com/britned/empire-platform-api/compare/v0.178.3...v0.179.0) (2023-08-14)


### ⚠ BREAKING CHANGES

* **auctions:** rename value to bid for a BidGroup
* **auctions:** rename submitBids endpoints to submitAuctionBids for consistency
* **auctions:** add new endpoints for getting participant bids for an auction
* **auctions:** wrap price and capacity into value for LT bids results
* **auctions:** rename current 'getBids' endpoints to 'getBiddingResults'

### Features

* **auctions:** add new endpoints for getting participant bids for an auction
* **auctions:** rename current 'getBids' endpoints to 'getBiddingResults'
* **auctions:** rename submitBids endpoints to submitAuctionBids for consistency
* **auctions:** rename value to bid for a BidGroup
* **auctions:** wrap price and capacity into value for LT bids results

### [0.178.3](https://github.com/britned/empire-platform-api/compare/v0.178.2...v0.178.3) (2023-08-14)

> No changes affecting Participants.

### [0.178.2](https://github.com/britned/empire-platform-api/compare/v0.178.1...v0.178.2) (2023-08-14)

> No changes affecting Participants.

### [0.178.1](https://github.com/britned/empire-platform-api/compare/v0.178.0...v0.178.1) (2023-08-10)


### Refactoring

* common definition for 'id' as path param

## [0.178.0](https://github.com/britned/empire-platform-api/compare/v0.177.1...v0.178.0) (2023-08-10)


### ⚠ BREAKING CHANGES

* rename auctionProductType to productType where applicable
* rename direction to borderDirection where applicable
* rename timescale to timescales to reflect arrays

### Refactoring

* rename auctionProductType to productType where applicable
* rename direction to borderDirection where applicable
* rename timescale to timescales to reflect arrays

### [0.177.1](https://github.com/britned/empire-platform-api/compare/v0.177.0...v0.177.1) (2023-08-10)


### Refactoring

* common definitions for 'borderDirection' parameters
* common definitions for 'mtuSize' parameters
* common definitions for 'productType' parameters
* common definitions for 'timescale' parameters
* common definitions for 'timescales' parameters
* remove excess 'required: false' declarations from params

## [0.177.0](https://github.com/britned/empire-platform-api/compare/v0.176.9...v0.177.0) (2023-08-10)


### ⚠ BREAKING CHANGES

* use header params for singular participant and organisation ids
* use header params for arrays of participant and organisation ids

### Refactoring

* use header params for arrays of participant and organisation ids
* use header params for singular participant and organisation ids

### [0.176.9](https://github.com/britned/empire-platform-api/compare/v0.176.8...v0.176.9) (2023-08-09)

> No changes affecting Participants.

### [0.176.8](https://github.com/britned/empire-platform-api/compare/v0.176.7...v0.176.8) (2023-08-09)


### Features

* **manual-file-upload:** reflect that EIC codes are sent in documents instead of internal IDs

### [0.176.7](https://github.com/britned/empire-platform-api/compare/v0.176.6...v0.176.7) (2023-08-09)


### Bug Fixes

* **auctions:** rename returnsWindowOpen to returnsWindowClose

### [0.176.6](https://github.com/britned/empire-platform-api/compare/v0.176.5...v0.176.6) (2023-08-09)

> No changes affecting Participants.
