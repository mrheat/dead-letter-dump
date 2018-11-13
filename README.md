Dead-Letter.email - Daily dump
================

Daily dump of the dead-letter.email lists for offline- and privacy aware lookups.

How to use
-------------

There are two lists available:

1. A blacklist, containing all disposable email address domains
2. A whitelist, containing all whitelisted domains

Both lists are available in JSON and XML format. Choose, whatever you prefer.

Every list contains at least a property `hash`, which represents a hashed version of the actual domain. While the whitelist also contains a property `domain`, which represents a domain in a readable format, the blacklist doesn't.

The hash is generated using double SHA1: `SHA1(SHA1(domain))`.

Statistics
-------------

- Last update was on November 14, 2018, 12:00 am
- The Whitelist currently contains 405 entries
- The Blacklist currently contains 32061 entries

## Support on BMC
Hey! Help us out with some cups of :coffee:!

[![BMC](https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg)](https://www.buymeacoff.ee/softcreatr)
