WMQ Monitoring Tool
==============

[A web-based monitoring tool for IBM® WebSphere® MQ](http://www.ibm.com/developerworks/websphere/library/techarticles/1311_jin/1311_jin.html), it targets WebSphere MQ administrators and users who would like to take advantage of the monitoring tool features, such as visualization of WebSphere MQ system health and custom alert conditions for WebSphere MQ objects, including queues, topics, channels, listeners, and queue managers.


## Documentation
* [Introduction](https://github.com/wmq-monitoring/wmq-monitoring/wiki/Introduction)
* [Installation](https://github.com/wmq-monitoring/wmq-monitoring/wiki/Installation)
* [FAQ](https://github.com/wmq-monitoring/wmq-monitoring/wiki/FAQ)

**NOTE**: Please read the documents shipped with the distribution package `wmq-monitoring-VERSION.zip`, the IBM developerWorks [article](http://www.ibm.com/developerworks/websphere/library/techarticles/1311_jin/1311_jin.html) is out of date, since we are continue improving this tool.

## Releases

### 0.2.2 Release (2015-6-29)
  - Supports MQ V7.0 and higher
  - Fixed incorrect alert, e.g. rule= warn(currentQDepth>100), error(currentQDepth>500)', currentQDepth=36 will generate WARN alert.
  - Fixed statistics cache size which is incorrectly configured.
  - Fixed incorrect platform value for IBM i and HP Integrity NonStop Server.
  - Fixed issues when deploying to GlassFish Server V4.
  - Drop in replacement for V0.2.1
  - Download from dropbox [wmq-monitoring-v0.2.2.zip](https://dl.dropboxusercontent.com/u/68813606/wmq-monitoring/wmq-monitoring-0.2.2.zip) or from mega [wmq-monitoring-v0.2.2.zip](https://mega.co.nz/#!Zg0yCBaZ!Aep5NS3KSFVDFQRW35rtaCvCVrWA4p6aSoeyRdBdUAI)

### 0.2.1 Release (2014-10-22) 
  - Supports MQ V7.0 and higher
  - Fixed some bugs and improved stability
  - Download from here [wmq-monitoring-v0.2.1.zip](https://dl.dropboxusercontent.com/u/68813606/wmq-monitoring/wmq-monitoring-0.2.1.zip) 
  -  **NOTE**: Fix bug: incorrect alert, e.g. `rule= warn(currentQDepth>100), error(currentQDepth>500)'`, but `currentQDepth=36` will generate `WARN` alert which is wrong.  Please download [wmq-monitoring-0.2.1.jar]( https://dl.dropboxusercontent.com/u/68813606/wmq-monitoring/bugfix/0.2.1/wmq-monitoring-0.2.1.jar) and [jsr305-2.0.2.jar]( https://dl.dropboxusercontent.com/u/68813606/wmq-monitoring/bugfix/0.2.1/jsr305-2.0.2.jar), just drop them to `WEB-INF/lib` to fix this issue.
  

### 0.2.1 RC1 (2014-5-13) 
  - Supports MQ V7.0 and higher
  - Download from here [wmq-monitoring-v0.2.1_RC1.zip](https://dl.dropboxusercontent.com/u/68813606/wmq-monitoring/wmq-monitoring-0.2.1_RC1.zip) 
  

###  0.2 Release (2013-11-18) 
  - Supports MQ V7.1 and higher
  - Download from here [wmq-monitoring-v0.2.zip](https://dl.dropboxusercontent.com/u/68813606/wmq-monitoring/wmq-monitoring-v0.2.zip) 
