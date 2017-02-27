salandur.php
============

[![Build Status](https://travis-ci.org/salandur/ansible-php-apache.svg?branch=master)](https://travis-ci.org/salandur/ansible-php-apache)

Ansible role to manage PHP configuration for Apache

### Example:

```yaml
- hosts: all

  roles:
    - salandur.php-apache
```

### Dependencies:

- salandur.php

### Variables

```yaml
php_modules: []
php_short_open_tag: Off
php_display_errors: Off
php_error_reporting: E_ALL & ~E_DEPRECATED
```

### License

Licensed under the MIT License. See the LICENSE file for details.

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/salandur/ansible-php-apache/issues)!
