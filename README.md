Guzzle Factory
==================

Guzzle Factory was created by, and is maintained by [Graham Campbell](https://github.com/GrahamCampbell), and provides a simple Guzzle 6 factory, with good defaults. Feel free to check out the [change log](CHANGELOG.md), [releases](https://github.com/GrahamCampbell/Guzzle-Factory/releases), [license](LICENSE), and [contribution guidelines](CONTRIBUTING.md).

<p align="center">
<a href="https://styleci.io/repos/88412277"><img src="https://styleci.io/repos/88412277/shield" alt="StyleCI Status"></img></a>
<a href="https://travis-ci.org/GrahamCampbell/Guzzle-Factory"><img src="https://img.shields.io/travis/GrahamCampbell/Guzzle-Factory/master.svg?style=flat-square" alt="Build Status"></img></a>
<a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="Software License"></img></a>
<a href="https://github.com/GrahamCampbell/Guzzle-Factory/releases"><img src="https://img.shields.io/github/release/GrahamCampbell/Guzzle-Factory.svg?style=flat-square" alt="Latest Version"></img></a>
</p>


## Installation

Guzzle Factory requires [PHP](https://php.net) 7. To get the latest version, simply require the project using [Composer](https://getcomposer.org):

```bash
$ composer require graham-campbell/guzzle-factory
```


## Usage

```php
<?php

use GrahamCampbell\GuzzleFactory\GuzzleFactory;

$client = GuzzleFactory::make(['base_uri' => 'https://example.com']);
```


## Security

If you discover a security vulnerability within this package, please send an e-mail to Graham Campbell at graham@alt-three.com. All security vulnerabilities will be promptly addressed.


## License

Guzzle Factory is licensed under [The MIT License (MIT)](LICENSE).