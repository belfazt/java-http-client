# Change Log
All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](http://semver.org/).

## [2.3.4] - 2016-08-09
### Fix
- [Pull #7](https://github.com/sendgrid/java-http-client/pull/7): Fix Response Charset to UTF-8
- Fixes [issue #6](https://github.com/sendgrid/java-http-client/issues/6): Multi-byte character got garbled on received mail
- BIG thanks to [Yoichi Kikuta](https://github.com/kikutaro) for the pull request!

## [2.3.3] - 2016-08-08
### Added
- Pull request [#11](https://github.com/sendgrid/java-http-client/pull/11)
- Solves [issue #10](https://github.com/sendgrid/java-http-client/issues/10): Improve Error Handling
- Now error messages are passed through from the server
- BIG thanks to [shuron](https://github.com/shuron) / [Alexander Holbreich](https://github.com/aholbreich) for the pull request!

## [2.3.2] - 2016-07-18
### Fixed
- 2.3.1 did not upload correctly

## [2.3.1] - 2016-07-08
### Fixed
- [Fix charset: Use "UTF-8" charset instead of default "ISO-8859-1"](https://github.com/sendgrid/java-http-client/pull/5)
- Thanks [DanailMinchev](https://github.com/DanailMinchev)!

## [2.3.0] - 2016-06-10
### Added
- Automatically add Content-Type: application/json when there is a request body

## [2.2.1] - 2016-06-08
### Fixed
- Set client properly when testing

## [2.2.0] - 2016-06-08
### Added
- Can pass test flag to allow for http calls

## [2.1.0] - 2016-06-08
### Added
- DELETE can now have a request body

## [2.0.0] - 2016-06-03
### Changed
- Made the Request and Response variables non-redundant. e.g. request.requestBody becomes request.body

## [1.0.0] - 2016-04-15
### Added
- We are live!
