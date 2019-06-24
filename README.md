# OrocrmFirstnameApiBundle

## Introduction
Define Oro Contact 'firstName' field as filter and sorter in OroCRM REST JSON API.

Originated from:

* https://github.com/oroinc/crm/issues/306
* https://github.com/oroinc/crm/pull/307

## Installation

```bash
$ composer require pedrofurtado/orocrm-firstname-api-bundle
```

# Commands
After installation of this Oro Bundle, execute in root folder of oro project:

```bash
$ php app/console oro:api:cache:clear
$ php app/console oro:api:doc:cache:clear
$ php app/console cache:clear
$ php app/console oro:migration:load --force --show-queries
```

Then, restart the application, clear all caches, and enjoy it!
