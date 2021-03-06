# Flask-HTTPAuth Change Log

## Release 3.2.2 - 2017-01-29

- Validate authorization header in multi auth ([#51](https://github.com/miguelgrinberg/Flask-HTTPAuth/issues/51))

## Release 3.2.1 - 2016-09-04

- Added `__version__` to top-level package
- Added readme and license files to package

## Release 3.2.0 - 2016-08-20

- Changed license to MIT
- Fix TCP Connection reset by peer error ([#39](https://github.com/miguelgrinberg/Flask-HTTPAuth/pull/39))

## Release 3.1.2 - 2016-04-20

- Make password check more robust.

## Release 3.1.1 - 2016-03-24

- `MultiAuth` class did not pass parameters to decorated function. ([#35](https://github.com/miguelgrinberg/Flask-HTTPAuth/issues/35))

## Release 3.1.0 - 2016-03-13

- Added `MultiAuth` class, to allow the combination of multiple authentication methods.
- Added additional test for token authentication
- Added a few examples

## Release 3.0.2 - 2016-03-11

- Invoke `verify_password` callback with no authentication when the provided authentication does not match the scheme

## Release 3.0.1 - 2016-03-09

- Prevented crash when client sends an invalid authorization header for token auth

## Release 3.0.0 - 2016-03-06

- Added token authentication support
- Switch Travis CI builds to use tox
- Refactored tests into separate test packages for each authentication method
- Added explicit Python 2 and 3 classifiers to setup script

## Release 2.7.1 - 2016-02-07

- Correctly obtain nonce and opaque values in `authenticate_header` function
- Documentation updates

## Release 2.7.0 - 2015-09-19

- Support custom authentication scheme and realm

## Release 2.6.0 - 2015-08-22

- Added callbacks for custom digest auth nonce/opaque generation
- Documentation updates
- Travis CI builds

## Release 2.5.0 - 2015-04-25

- In digest auth, support the client providing a pre-generated "ha1" instead of plain text password
- Add "ha1" generation helper function for digest auth
- Documentation updates

## Release 2.4.0 - 2015-03-01

- Support anonymous users in `verify_password` callback
- Unit test fixes

## Release 2.3.0 - 2014-09-23

- Corrections to `hash_password` and `verify_password` decorators
- Bypass authentication for `OPTIONS` requests
- Pep8 compliance

## Release 2.2.1 - 2014-03-16

- Fixed documentation examples
- Corrections to `get_password` decorator implementation

## Release 2.2.0 - 2013-11-25

- Build fixes

## Release 2.1.0 - 2013-09-27

- Support optionally passing the username to the hash password callback

## Release 2.0.0 - 2013-09-26

- Changed `auth.username` property to a `auth.username()` function
- Documentation updates

## Release 1.1.0 - 2013-08-30

- Python 3 support
- Documentation updates

## Release 1.0.0 - 2013-07-27

- First official release

