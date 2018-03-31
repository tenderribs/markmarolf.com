#markmarolf cool web

## how to setup
config your mailgun apikey and domain in config/mailgun.php

```php
$mgClient = new Mailgun('api-key', new \Http\Adapter\Guzzle6\Client());
$mgDomain = "mg.yourdomain.com";
```

kkthxbye
