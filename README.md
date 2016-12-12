# check_mysqldump-secure

Nagios Plugin to monitor the state of MySQL database backups: Success, last backup, encryped, compressed, etc.

[![Build Status](https://travis-ci.org/cytopia/check_mysqldump-secure.svg?branch=master)](https://travis-ci.org/cytopia/check_mysqldump-secure)
[![Latest Stable Version](https://poser.pugx.org/cytopia/check_mysqldump-secure/v/stable)](https://packagist.org/packages/cytopia/check_mysqldump-secure) 
[![Latest Unstable Version](https://poser.pugx.org/cytopia/check_mysqldump-secure/v/unstable)](https://packagist.org/packages/cytopia/check_mysqldump-secure) 
[![Total Downloads](https://poser.pugx.org/cytopia/check_mysqldump-secure/downloads)](https://packagist.org/packages/cytopia/check_mysqldump-secure) 
[![POSIX](https://img.shields.io/badge/posix-100%25-brightgreen.svg)](https://en.wikipedia.org/?title=POSIX)
[![Type](https://img.shields.io/badge/type-%2Fbin%2Fsh-red.svg)](https://en.wikipedia.org/?title=Bourne_shell)
[![License](https://poser.pugx.org/cytopia/check_mysqldump-secure/license)](http://opensource.org/licenses/MIT)

---

| [![Awesome-Nagios-Plugins](https://raw.githubusercontent.com/cytopia/awesome-nagios-plugins/master/doc/img/awesome-nagios.png)](https://github.com/cytopia/awesome-nagios-plugins) | Find more plugins at [Awesome Nagios](https://github.com/cytopia/awesome-nagios-plugins) |
|---|---|
| [![Icinga Exchange](https://raw.githubusercontent.com/cytopia/awesome-nagios-plugins/master/doc/img/icinga.png)](https://exchange.icinga.com/cytopia) | **Find more plugins at [Icinga Exchange](https://exchange.icinga.com/cytopia)** |
| [![Nagios Exchange](https://raw.githubusercontent.com/cytopia/awesome-nagios-plugins/master/doc/img/nagios.png)](https://exchange.nagios.org/directory/Owner/cytopia/1) | **Find more plugins at [Nagios Exchange](https://exchange.nagios.org/directory/Owner/cytopia/1)** |

---

**Features**:

* Did every database dump correctly?
* Is the last dump within the specified time cycle?
* If encryption is required, was the dump encryted?
* If compression is required, was the dump compressed?
* If logging is required, was the dump logged?


**Additional information is displayed. Such as:**

* How many databases dumped
* How many databases skipped
* How long did it take to dump everything
* How many megabytes have been dumped

# How to use it
You will either have to generate a [logfile](mysqldump-secure.nagios.log) that is parseable by the [check_mysqldump-secure](check_mysqldump-secure) script (see [mysqldump-secure.nagios.log](mysqldump-secure.nagios.log) for explanation) or you can use the already existing tool to dump MySQL databases in a secure way, which supports Nagios log output.
[mysqldump-secure](https://github.com/cytopia/mysqldump-secure)


# Nagios / Icinga Integration

## Monitoring Data
![OK](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/overview_ok.png)
![Unknown](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/overview_unknown.png)
![Error](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/overview_error.png)
![Error](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/overview_error2.png)

## Long Plugin Output
This is only applicable to nagios >= 3
![OK](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/additional_information.png)


## Log
![Log](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/log.png)


## Performance Date

![Ago](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/graph_hours_ago.png)
![Time](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/graph_time.png)
![Size](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/graph_size.png)
![Total](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/graph_total_dbs.png)
![Ignored](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/graph_ignored_dbs.png)
![Tmpwatch](https://raw.githubusercontent.com/cytopia/check_mysqldump-secure/master/doc/graph_tmpwatch_deletions.png)


## Awesome

Added by the following [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) lists:

* [awesome-nagios-plugins](https://github.com/cytopia/awesome-nagios-plugins)
