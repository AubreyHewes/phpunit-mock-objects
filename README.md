[![Latest Stable Version](https://poser.pugx.org/phpunit/phpunit-mock-objects/v/stable.png)](https://packagist.org/packages/phpunit/phpunit-mock-objects)
[![Build Status](https://travis-ci.org/AubreyHewes/phpunit-mock-objects.png?branch=master)](https://travis-ci.org/AubreyHewes/phpunit-mock-objects)

# PHPUnit_MockObject

NOTE: This is a version that re-introduces `staticExpects` for bc reasons.

**PHPUnit_MockObject** is the default mock object library for PHPUnit.

## Requirements

* PHP 5.3.3 is required but using the latest version of PHP is highly recommended

## Installation

To add PHPUnit_MockObject as a local, per-project dependency to your project, simply add a dependency on `phpunit/phpunit-mock-objects` to your project's `composer.json` file. Here is a minimal example of a `composer.json` file that just defines a dependency on PHPUnit_MockObject 2.0:

    {
        "require": {
            "phpunit/phpunit-mock-objects": "dev-master as 2.3.x-dev"
        },
        "repositories": [
            {
                "type": "git",
                "url": "https://github.com/AubreyHewes/phpunit-mock-objects"
            }
        ]
    }

