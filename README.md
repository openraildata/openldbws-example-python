OpenLDBWS Python Example
========================

This repository contains examples of how to use the National Rail Live
Departure Boards Web Service (OpenLDBWS), located at the following URL:

* https://lite.realtime.nationalrail.co.uk/OpenLDBWS/

To use the service, you will need a token which is available by
signing up at the following URL:

* https://realtime.nationalrail.co.uk/OpenLDBWSRegistration/

Edit `getDepartureBoardExample.py` and set `LDB_TOKEN` to your own token.

Install [Zeep](https://python-zeep.readthedocs.io/en/master/) using `pip`:

`pip install zeep`  

Running `getDepartureBoardExample.py` will show you departures for
London Euston.

Updating the WSDL
-----------------

Periodically, a new version of the WSDL will be released at:

* https://lite.realtime.nationalrail.co.uk/OpenLDBWS/

This code is written for version 2017-10-01.  To update it to use a
later version, edit `getDepartureBoardExample.py` and change the `WSDL`
variable.  

Support
-------

This code has been tested on Python 3.6.7 and 2.7.15.

For support and questions with using the OpenLDBWS, please use the
forum at the following URL:
 
 * https://groups.google.com/group/openraildata-talk