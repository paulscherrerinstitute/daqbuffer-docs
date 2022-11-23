# TLS termination for SwissFEL DAQ buffer

![Diagram 1](sf-http-flow.drawio.svg)

For network compliance:

* TLS is handled by nginx
* Network border crossing only with TLS
* Applications don't talk TLS (neither as server nor client)
