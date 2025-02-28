SMSAPI Notifier
===============

Provides [Smsapi](https://ssl.smsapi.pl) integration for Symfony Notifier.

DSN example
-----------

```
SMSAPI_DSN=smsapi://TOKEN@default?from=FROM&fast=FAST
```

where:
 - `TOKEN` is your API Token (OAuth)
 - `FROM` is the sender name
 - `FAST` setting this parameter to "1" (default "0") will result in sending message with the highest priority which ensures the quickest possible time of delivery. Attention! Fast messages cost more than normal messages.

See your account info at https://ssl.smsapi.pl/

Resources
---------

 * [Contributing](https://symfony.com/doc/current/contributing/index.html)
 * [Report issues](https://github.com/symfony/symfony/issues) and
   [send Pull Requests](https://github.com/symfony/symfony/pulls)
   in the [main Symfony repository](https://github.com/symfony/symfony)
