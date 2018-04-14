# The MacPorts Guide

This is the MacPorts documentation directory.
## Building

To generate it you have to checkout the entire "macports-guide" repository,
and you need the "docbook-xsl", "docbook-xml-5.0" and "libxslt" ports.
If your port installation isn't in /opt/local, edit or override the
PREFIX Makefile variable.

### HTML Output

To generate the guide just run "make" in this directory; the HTML version will
be placed in guide/html.

### PDF Output

To generate a PDF version of the guide, use "make guide-dblatex". This
requires the "dblatex" port.