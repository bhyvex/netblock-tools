netblock tools
===============

Documentation
--------
For installation instructions and information on the design overview
of the netblock-tools scripts, please read the documentation that is found here
and on wiki.

Purpose
-------
This set of console tools help in DDOS attack protection.

Dependences
--------
- python >= 2.4.3


Contents
--------

- **netblock.py**           - Create rules for Iptables that block or allow networks by country code from GeoIP database.
- **netnull.py**            - Create rules for ip route that block or allow networks by country code from GeoIP database.
- **ipblock.py**            - Add blocking rules to Iptables on the base of any access logs (http, ftp, etc.)
- **ipblock.config**        - Config file for ipblock

Installing
----------
Checkout scripts and run -h.

Running examples
----------
1. ./netblock.py CH | bash
2. tail -f /var/log/httpd/access_log | ipblock.py /etc/ipblock.config -f -

Questions?
----------

If you have questions about netblock tools, or problems getting things
working, first try searching wiki.

If all else fails, you can email me and I'll try and respond as
soon as I get a chance.

        -- Andrey V. Scopenco (andrey@scopenco.net)

