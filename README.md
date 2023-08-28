# rslv

Provides a FastAPI implementation of an identifier resolver.

The rslv  implementation provides a generic identifier resolution service that may be adapted to support different schemes.
The base requirement is that identifiers are of the form `scheme:value` where scheme is a scheme name (e.g. "doi" or "ark") and
value is the value of the identifier (e.g. `10.12345/foo` or `99999/fd99`).


