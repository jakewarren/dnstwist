Change log
==========

This is the list of all noteworthy changes made in every release of the tool.

dnstwist 1.1
------------

- Added --mxcheck option to test if SMTP servers from DNS MX record can be used
  to intercept misdirected e-mails.
- Added --dictionary option to generate additional domain variants.
- Added URL parser which extends --ssdeep functionality.
- Added new glyph definitions to the homoglyph fuzzing function.
- Added local copies of GeoIP and TLD databases.
- Added a few various and common phishing domain transforms.

dnstwist 1.0
------------

- First stable release with multithreaded job distribution.
- Extra features include: evaluating web pages similarity with fuzzy hashes,
  banner grabbing for HTTP and SMTP, GeoIP and WHOIS lookups.
