# DAQ buffer docs and design

## HTTP / HTTPS setup

[TLS termination for SwissFEL setup](sf-http-flow.md)

For network compliance:

* TLS is handled by nginx
* Network border crossing only with TLS
* Applications don't talk TLS (neither as server nor client)
