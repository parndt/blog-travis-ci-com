---
title: "Upcoming Build Environment Updates"
created_at: Thu 24 Jul 2014 08:46:36 CEST
author: Hiro Asari
twitter: hiro_asari
layout: post
permalink: 2014-07-24-upcoming-build-environment-updates
---

New build environments updates are coming.

It has been a while since our last build environmetnt update in
[late April](http://blog.travis-ci.com/2014-04-28-upcoming-build-environment-updates/),
and we thought it was a good time for the next set of updates.

## Updated rollout schedule

We are pushing back the .org update by one day to **[08:00 UTC on the 30th of July](http://everytimezone.com/#2014-7-30,-240,cn3)**.
The update for travis-ci.com will be carried out on the 31st as planned.
We apologize for the inconvenience.

## Update schedule

The updates will be rolled out to
**[travis-ci.org](https://travis-ci.org)** at **[08:00 UTC on the 29th of July](http://everytimezone.com/#2014-7-29,-240,cn3)** and
to **[travis-ci.com](https://travis-ci.com)** at **[06:00 UTC on the 31st of July](http://everytimezone.com/#2014-7-31,-360,cn3)**.

## Build Environment Updates

All build environments will be receiving some fantastic updates.

For all environments, Go 1.3 is now the default.

### Android VM

We've introduced [Android support back in May](2014-05-07-android-build-support-now-in-beta),
and you have been busy testing it out.
Google has since released a new SDK, and it is now time for us to catch up.

This update includes SDK 23 support and other component updates.

### Erlang VM

Erlang 17.1 is now available.

### Go VM

Version 1.2.2 is also preinstalled.

### Node.js VM

Default is now version 0.10.29.

### Perl VM

Version updates include:

* 5.20.0 and 5.21.0 have been added.
* Older development versions 5.17 and 5.19 have been removed.
* 5.18.2 and 5.20.0 are now also provided with the `-Duseshrplib` compile option under the names
  `5.18-shrplib` and `5.20-shrplib`, respectively.

### PHP VM

Version updates include:

* 5.6.0rc2
* 5.5.14
* 5.4.30
* HHVM 3.2.0

We also added LDAP support.

### Python VM

Following updates are included:

* Python 2.7.8
* Python 3.4.1
* PyPy3
* PyPy 2.3.1

### Ruby VM

#### MRI

We have added the following pre-installed Rubies:

* MRI 1.9.3-p547
* MRI 2.1.2

#### JRuby

We have updated JRuby to the latest release

* JRuby 1.7.13

#### Rubinius

* Rubinius 2.2.10 (Available as `rbx`; no longer needs to be specified as `rbx-2`)


### Services Updates

In addition, the following updates are available on all VMs:

* CouchDB update to latest stable (1.5)
* Cassandra 2.0.9
* Sphinx version updates (2.0.10, 2.1.8, 2.2.2-beta; 2.1.8 is default)
