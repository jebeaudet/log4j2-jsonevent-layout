# log4j2-jsonevent-layout

[![GitHub license](https://img.shields.io/badge/license-LGPL-blue.svg)](https://raw.githubusercontent.com/dubasdey/log4j2-jsonevent-layout/master/LICENSE)
[![Build Status](https://travis-ci.org/dubasdey/log4j2-jsonevent-layout.svg?branch=master)](https://travis-ci.org/dubasdey/log4j2-jsonevent-layout)


Log4j2 JSON Event Layout without requirement of thirdparty libraries

## Usage

Add the <JSONLog4j2Layout> to any appender.

## Attributes

* locationInfo - Adds location info to the Trace
* singleLine - Removes \r and \n in JSON String
* htmlSafe - Escapes additional characters to print the JSON on HTML pages.
* plainContextMap - Prints the content of the ContextMap in the root as __key:value__ instead of a contextMap object with the values
* charset - Charset to use (Default UTF-8)
* UserField - Collection of user fields with __key__ and __value__ that will be printed in the LogEntry


