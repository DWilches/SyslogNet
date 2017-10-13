SyslogNet
=========

**This repository is a fork of https://github.com/emertechie/SyslogNet with the added ability to use the SyslogNet functions as asynchronous code: the original code blocks doing all I/O operations, with the modifications of this repo all I/O is done asynchronously. This means your program don't need to wait as much when doing network operations as with the original code.**

.Net Syslog client. Supports both RFC 3164 and RFC 5424 Syslog standards as well as UDP and encrypted TCP transports.

Installation
============

Available on NuGet:
```
Install-Package SyslogNet.Client
```
