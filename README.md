# betssh-api-client
PHP API Client for Bets.sh Casino v2.5

Example of usage:
```php
<?php
use betssh\betssh\api\client\Client;

require __DIR__.'/vendor/autoload.php';

$client = new Client(array(
        'url' => 'https://api.spins.sh',
        'sslKeyPath' => __DIR__.'/ssl/apikey.pem',
));

var_export($client->listGames());
```
