# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 76 ending 2018-01-01

### Fixed
- Return empy list instead of nil for responses with empty bodies [(#53)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/53)
- Fix protocol selection when adding a new nuage provider [(#45)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/45)
- Human readable error when selecting wrong security protocol [(#43)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/43)

## Unreleased as of Sprint 74 ending 2017-11-27

### Fixed
- Fix exception handing for credential validation on raw_connect [(#40)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/40)

## Unreleased as of Sprint 72 ending 2017-10-30

### Added
- Enable Nuage network manager [(#33)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/33)
- Update raw_connect to simplify validation from UI [(#32)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/32)
- Use AMQP fallback endpoints when available [(#30)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/30)
- Connect events to targeted refresh [(#28)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/28)
- Implement targeted refresh for NetworkManager [(#20)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/20)

## Gaprindashvili Beta1

### Added
- Implement graph inventory refresh for network manager [(#13)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/13)
- Provide extensive unit tests for legacy refresher [(#12)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/12)
- Install qpid_proton for Travis [(#11)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/11)

### Fixed
- Fix a problem when no policy groups exist [(#4)](https://github.com/ManageIQ/manageiq-providers-nuage/pull/4)
