# Changelog

## v0.3
* Breaking Changes!
* Drop the `fastly_duration` log value
* Add the ability to change verbosity. Log levels warn/debug will return everything from 0.2 minus fastly_duration. Log levels info/error will return a subset of warn/debug that is missing params, client_ip, & client_version.

## v0.2
* Add support for error logging tagged with the request id. Errors now are bunched up as a single JSON message in addition to the standard output for easier parsing of errors and matching requests to the resulting error.
