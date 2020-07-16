# Calculator

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Total Downloads][ico-downloads]][link-downloads]
[![Build Status][ico-travis]][link-travis]
[![StyleCI][ico-styleci]][link-styleci]

This is where your description should go. Take a look at [contributing.md](contributing.md) to see a to do list.

## Installation

Via Composer

``` bash
$ composer require mergimu/calculator
```

## Usage
```bash
use MergimU\Calculator\Facades\Calculator;
Calculator::initialValue(number)->add(number)->getResult()

Available methods: 
intitalValue(number -> default = 0)
add(number)
subtract(number)
multiply(number)
square()
clear()
getResult()
```

## Change log

Please see the [changelog](changelog.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [contributing.md](contributing.md) for details and a todolist.

## Security

If you discover any security related issues, please email mergimuka1@gmail.com instead of using the issue tracker.

## Credits

- [Mergim Uka][link-author]
- [All Contributors][link-contributors]

## License

MIT. Please see the [license file](license.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/mergimu/calculator.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/mergimu/calculator.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/mergimu/calculator/master.svg?style=flat-square
[ico-styleci]: https://styleci.io/repos/12345678/shield

[link-packagist]: https://packagist.org/packages/mergimu/calculator
[link-downloads]: https://packagist.org/packages/mergimu/calculator
[link-travis]: https://travis-ci.org/mergimu/calculator
[link-styleci]: https://styleci.io/repos/12345678
[link-author]: https://github.com/MergimUkaa
[link-contributors]: ../../contributors
