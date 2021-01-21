CMPUT404-assignment-webserver
=============================

CMPUT404-assignment-webserver

See requirements.org (plain-text) for a description of the project.

Make a simple webserver.

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.

server.py contains contributions from:

* Abram Hindle
* Eddie Antonio Santos
* Jackson Z Chang
* Mandy Meindersma 

But the server.py example is derived from the python documentation
examples thus some of the code is Copyright © 2001-2013 Python
Software Foundation; All Rights Reserved under the PSF license (GPL
compatible) http://docs.python.org/2/library/socketserver.html

<b>Requirement<b>
- [ ] The webserver can serve files from ./www
- [ ] The webserver can be run using the runner.sh file
- [ ] The webserver can pass all the tests in freetests.py
- [ ] The webserver can pass all the tests in not-free-tests.py (you only have part of this one, I reserve the right to add tests)
- [ ] The webserver supports mime-types for HTML
- [ ] The webserver supports mime-types for CSS
- [ ] The webserver can return index.html from directories (paths that end in /)
- [ ] The webserver can server 404 errors for paths not found
- [ ] The webserver works with Firefox and Chromium http://127.0.0.1:8080/
- [ ] The webserver can serve CSS properly so that the front page has an orange h1 header.
- [ ] I can check out the source code via an HTTP git URL
- [ ] Provide 1 screenshot (commit and push it!) of Firefox at http://127.0.0.1:8080/ as ./root.png in the root of the repo
- [ ] Provide 1 screenshot (commit and push it!) of Firefox at http://127.0.0.1:8080/deep/ as ./deep.png in the root of the repo
- [ ] Return a status code of “405 Method Not Allowed” for any method you cannot handle (POST/PUT/DELETE)
- [ ] Must use 301 to correct paths such as http://127.0.0.1:8080/deep to http://127.0.0.1:8080/deep/ (path ending)
