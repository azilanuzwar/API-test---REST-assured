What do I need to run these samples?
---
A Java 8 JDK and Maven. That's it.

What API is used for the samples?
---
The code samples invoke the [Zippopotam.us API](http://api.zippopotam.us).

In those cases where the actual API could not be used (it doesn't support HTTP operations other than GET, plus it doesn't have an option to return XML response bodies), calls have been mocked using [WireMock](http://wiremock.org). 
