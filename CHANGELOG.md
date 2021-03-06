# Stripe Checkout Changelog

All notable changes to this project will be documented in this file.

## 1.0.7 - 2018-04-10

### Changed
- Renamed the composer package name to `craft-stripecheckout`
- Set Craft CMS minimum requirement to `^3.0.1`
- Set Stripe minimum requirement to `^6.5.0`

## 1.0.6 - 2018-04-09

### Changed
- `{{ csrfInput() }}` added to docs

### Fixed
- Require admin no longer enforced in templates

## 1.0.5 - 2018-04-06

### Added
- added `beforeSave` and `afterSave` events to the Charge Service (credit [@cole007](https://github.com/cole007))

## 1.0.4 - 2018-03-06

### Fixed
- Issue retrieving charges within prefixed tables

## 1.0.3 - 2018-02-26

### Changed
- Set Craft CMS minimum requirement to `^3.0.0-RC11`
- Set Stripe minimum requirement to `^5.9.2`

## 1.0.2 - 2018-01-14

### Changed
- Screenshot added to README.md

### Fixed
- Typos

## 1.0.1 - 2018-01-14

### Added
- Webhook endpoint URL displayed on plugin settings page

## 1.0.0 - 2018-01-13

### Added
- Initial release
