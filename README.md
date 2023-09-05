# Predis #

[![Software license][ico-license]](LICENSE)
[![Latest stable][ico-version-stable]][link-packagist]
[![Latest development][ico-version-dev]][link-packagist]
[![Monthly installs][ico-downloads-monthly]][link-downloads]
[![Build status][ico-travis]][link-travis]

Flexible and feature-complete [Redis](http://redis.io) client for PHP >= 7.4 and HHVM >= 2.3.0.

Predis does not require any additional C extension by default, but it can be optionally paired with
[phpiredis](https://github.com/nrk/phpiredis) to lower the overhead of the serialization and parsing
of the [Redis RESP Protocol](http://redis.io/topics/protocol).

More details about this project can be found on the [frequently asked questions](FAQ.md).

### Fork From Predis ###

[Predis](https://github.com/predis/predis)

### License ###

The code for Predis is distributed under the terms of the MIT license (see [LICENSE](LICENSE)).

[ico-license]: https://img.shields.io/github/license/predis/predis.svg?style=flat-square
[ico-version-stable]: https://img.shields.io/packagist/v/predis/predis.svg?style=flat-square
[ico-version-dev]: https://img.shields.io/packagist/vpre/predis/predis.svg?style=flat-square
[ico-downloads-monthly]: https://img.shields.io/packagist/dm/predis/predis.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/predis/predis.svg?style=flat-square
[ico-hhvm]: https://img.shields.io/hhvm/predis/predis.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/predis/predis
[link-travis]: https://travis-ci.org/predis/predis
[link-downloads]: https://packagist.org/packages/predis/predis/stats
