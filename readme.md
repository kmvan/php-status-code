### INSTALL

```shell
composer require kmvan/status-code
```

### REQUIRED

- PHP 8.1 or later

### USAGE

```php
<?php

use Kmvan/StatusCode;

echo StatusCode::OK; // output int 200
echo StatusCode::BAD_REQUEST; // output int 400
```
