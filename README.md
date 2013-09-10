Zimbra Python Client
====================

Report a bug at: http://github.com/ilgarm/pyzimbra/issues

Documentation available online at: http://trac.lab.az/pyzimbra/wiki

Testing
-------
Unit testing is provided through [unittest]. Because of the nature of pyzimbra,
you need to provide credentials and a test server to make tests. So:

    $ cd test
    $ cp test.properties.example test.properties

Adapt test/test.properties to your needs. You can now run the test suite:

    $ ./tests/run_all_tests.py

[unittest]: http://docs.python.org/2/library/unittest.html

Release notes
-------------

version 0.1 - current

* ticket:2 - zimbra client authentication
* ticket:8 - zimbra soap wrapper
* ticket:22 - rewrite all xml manipulations to use single library, minidom or lxml.etree
* ticket:31 - add proxy support
* ticket:27 - error and exception handling
* ticket:33 - switch to SOAPpy
* ticket:20 - zimbra client preauthentication
* ticket:21 - zimbra client administrative authentication