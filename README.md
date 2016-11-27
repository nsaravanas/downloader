# Downloader

 Standalone application to download/copy files from different protocols. For known protocols `http`, `https`, `ftp` and `file` handler is not requied, for other protocols handler should be provided and an entry needs to be added in `url.stream.handlers`

example `url.stream.handlers = telnet:org.saravana.handler.TelnetHandler,snmp:org.saravana.handler.SnmpHandler`

# Technologies

   1. Java 8
   2. SpringBoot 1.4.0
 
# Run

	java -jar downloader-{version}.jar [URLs]

# Build Status

[![Build Status](https://travis-ci.org/nsaravanas/downloader.svg?branch=master)](https://travis-ci.org/nsaravanas/downloader)