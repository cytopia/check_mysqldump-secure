# check_mysqldump-secure

[![Build Status](https://travis-ci.org/cytopia/check_mysqldump-secure.svg?branch=master)](https://travis-ci.org/cytopia/check_mysqldump-secure)
[![Latest Stable Version](https://poser.pugx.org/cytopia/check_mysqldump-secure/v/stable)](https://packagist.org/packages/cytopia/check_mysqldump-secure) 
[![Latest Unstable Version](https://poser.pugx.org/cytopia/check_mysqldump-secure/v/unstable)](https://packagist.org/packages/cytopia/check_mysqldump-secure) 
[![Total Downloads](https://poser.pugx.org/cytopia/check_mysqldump-secure/downloads)](https://packagist.org/packages/cytopia/check_mysqldump-secure) 
[![POSIX](https://img.shields.io/badge/posix-100%25-brightgreen.svg)](https://en.wikipedia.org/?title=POSIX)
[![Type](https://img.shields.io/badge/type-%2Fbin%2Fsh-red.svg)](https://en.wikipedia.org/?title=Bourne_shell)
[![License](https://poser.pugx.org/cytopia/check_mysqldump-secure/license)](http://opensource.org/licenses/MIT)

Nagios Plugin to monitor the state of mysql database dumps. The following states are reported:
* Did every database dump correctly?
* Is the last dump within the specified time cycle?
* If encryption is required, was the dump encryted?
* If compression is required, was the dump compressed?
* If logging is required, was the dump logged?
 
Additional information is displayed. Such as:
* How many databases dumped
* How many databases skipped
* How long did it take to dump everything
* How many megabytes have been dumped

It is planned to included dumping time and size into performance data, so you have a nice overview of when and how those two values have increased.
