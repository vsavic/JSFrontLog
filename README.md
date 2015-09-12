JavaScrip front-end logger
=============

JSFrontLog is used to catch all unhandled exeptions by passing full JavaScript stack trace, browser name, version and actual error message.

It contains custom log4net smtp appender, log level and http module to inject required JavaScript libraries.

##Configuration
The JSFrontLog library can be configured to include \ exclude current website screenshot in order to see if UI is messed up.
Additionaly it allows you to include other cross-domain images by enabling proxy.
