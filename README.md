Dead Letter Dump
================

Daily dump of disposable email address domain list for offline- and privacy aware lookups.

How to use
-------------

There are three lists available:

1. A blacklist, containing all disposable email address domains
2. A whitelist, containing all whitelisted domains
3. A greylist, containing all domains, which are blacklisted but marked as dead (no MX record).

All three lists are available in JSON and XML format. Choose, whatever you prefer.

Every list contains at least a property `hash`, which represents a hashed version of the actual domain. While the whitelist also contains a property `domain`, which represents a domain in a readable format, the grey- and blacklist don't.

Even if a domain is marked as dead, it's still included in the blacklist. Feel free to filter them out.

The hash is generated using double SHA1: `SHA1(SHA1(domain))`.

Statistics
-------------

- Last update was on December 17, 2018, 12:00 am
- The Whitelist currently contains 407 entries
- The Blacklist currently contains 32282 entries
- The Greylist currently contains 0 entries

## Support on BMC
Hey! Help us out with some cups of :coffee:!

[![BMC](https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg)](https://www.buymeacoff.ee/softcreatr)
