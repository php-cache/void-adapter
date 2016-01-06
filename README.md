# Void PSR-6 adapter 
[![Build Status](https://travis-ci.org/php-cache/void-adapter.svg?branch=master)](https://travis-ci.org/php-cache/void-adapter) [![codecov.io](https://codecov.io/github/php-cache/void-adapter/coverage.svg?branch=master)](https://codecov.io/github/php-cache/void-adapter?branch=master)

This is a void implementation of PSR-6. Other names for this adapter could be Blackhole or Null. This 
adapter does not save anything and will always return an empty CacheItem. 

| Feature |   |
| ------- | - | 
| Flush everything | No 
| Expiration time | No
| Support for tags | No