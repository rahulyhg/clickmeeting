# Clickmeeting

korealex/clickmeeting is a PHP 5.4+ REST API to easily add the powerful functionality of ClickMeeting Video Conferencing to your favorite applications.

This project adheres to a [Contributor Code of Conduct][conduct]. By participating in this project and its community, you are expected to uphold this code.


## About

From [Wikipedia](https://en.wikipedia.org/wiki/Web_conferencing):

> Web conferencing may be used as an umbrella term for various types of online collaborative services including web seminars ("webinars"), webcasts, and peer-level web meetings. It may also be used in a more narrow sense to refer only to the peer-level web meeting context, in an attempt to disambiguate it from the other types of collaborative sessions.[1] Terminology related to these technologies is inexact, and no generally agreed upon source or standards organization exists to provide an established usage reference.

> In general, web conferencing is made possible by Internet technologies, particularly on TCP/IP connections. Services may allow real-time point-to-point communications as well as multicast communications from one sender to many receivers. It offers data streams of text-based messages, voice and video chat to be shared simultaneously, across geographically dispersed locations. Applications for web conferencing include meetings, training events, lectures, or presentations from a web-connected computer to other web-connected computers.

Much inspiration for this API came from the ClickMeeting/DevZone repository.


## Installation

The preferred method of installation is via [Packagist][] and [Composer][]. Run the following command to install the package and add it as a requirement to your project's `composer.json`:

```bash
composer require korealex/clickmeeting
```

## Requirements



## API documentation

The [latest class API documentation][apidocs] is available online.

This project uses [ApiGen](http://apigen.org/) to generate this documentation. To generate the documentation on your own, install dev dependencies and run the following command from the root of the project:

```
./vendor/bin/apigen generate --source="src" --destination="build/apidocs" --title="ramsey/uuid" --template-theme="bootstrap" --deprecated --todo
```

This will generate documentation in the `build/apidocs/` folder.


## Examples


## Contributing

Contributions are welcome! Please read [CONTRIBUTING][] for details.


## Copyright and license

The korealex/clickmeeting API is copyright © [Alexis Rosa](https://alexisrosa.com/) and licensed for use under the MIT License (MIT). Please see [LICENSE][] for more information.

[packagist]: https://packagist.org/packages/korealex/clickmeeting
[composer]: http://getcomposer.org/
[apidocs]: http://docs.benramsey.com/ramsey-uuid/latest/

[badge-gitter]: https://img.shields.io/badge/gitter-join_chat-brightgreen.svg?style=flat-square
[badge-source]: https://img.shields.io/badge/source-ramsey/uuid-blue.svg?style=flat-square
[badge-release]: https://img.shields.io/packagist/v/ramsey/uuid.svg?style=flat-square
[badge-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[badge-build]: https://img.shields.io/travis/ramsey/uuid/master.svg?style=flat-square
[badge-quality]: https://img.shields.io/scrutinizer/g/ramsey/uuid/master.svg?style=flat-square
[badge-coverage]: https://img.shields.io/coveralls/ramsey/uuid/master.svg?style=flat-square
[badge-downloads]: https://img.shields.io/packagist/dt/ramsey/uuid.svg?style=flat-square

[gitter]: https://gitter.im/ramsey/uuid
[source]: https://github.com/ramsey/uuid
[release]: https://packagist.org/packages/ramsey/uuid
[license]: https://github.com/ramsey/uuid/blob/master/LICENSE
[build]: https://travis-ci.org/ramsey/uuid
[quality]: https://scrutinizer-ci.com/g/ramsey/uuid/
[coverage]: https://coveralls.io/r/ramsey/uuid?branch=master
[downloads]: https://packagist.org/packages/ramsey/uuid
