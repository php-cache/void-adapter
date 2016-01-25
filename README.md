# Void PSR-6 adapter 
[![Build Status](https://travis-ci.org/php-cache/void-adapter.svg?branch=master)](https://travis-ci.org/php-cache/void-adapter) [![codecov.io](https://codecov.io/github/php-cache/void-adapter/coverage.svg?branch=master)](https://codecov.io/github/php-cache/void-adapter?branch=master)

This is a void implementation of PSR-6. Other names for this adapter could be Blackhole or Null. This 
adapter does not save anything and will always return an empty CacheItem. 

### Install

```bash
composer require cache/void-adapter
```

or add it to your composer.json

```json
"require": {
    "cache/void-adapter" : "~0.2"
}
```

### Usage

```php
use Cache\Adapter\Void\VoidCachePool;

$pool = new VoidCachePool();
```

| Feature | Supported |
| ------- | --------- | 
| Flush everything | No 
| Expiration time | No
| Tagging | Yes

### Contribute

Contributions are very welcome! Send us a pull request or report any issues you find on the [issue tracker](https://github.com/php-cache/issues/issues).
