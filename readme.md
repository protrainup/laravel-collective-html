![LaravelCollective HTML](LaravelCollectiveHTML-banner.png)

[![Build Status](https://travis-ci.org/LaravelCollective/html.svg)](https://travis-ci.org/LaravelCollective/html)
[![Total Downloads](https://poser.pugx.org/LaravelCollective/html/downloads)](https://packagist.org/packages/laravelcollective/html)
[![Latest Stable Version](https://poser.pugx.org/LaravelCollective/html/v/stable.svg)](https://packagist.org/packages/laravelcollective/html)
[![Latest Unstable Version](https://poser.pugx.org/LaravelCollective/html/v/unstable.svg)](https://packagist.org/packages/laravelcollective/html)
[![License](https://poser.pugx.org/LaravelCollective/html/license.svg)](https://packagist.org/packages/laravelcollective/html)

Official documentation for Forms & Html for The Laravel Framework can be found at the [LaravelCollective](https://laravelcollective.com/docs) website.

## Fork Info

This is a maintained fork of the abandoned `laravelcollective/html` package. It provides compatibility with modern Laravel and PHP versions.

**Supported versions:**
- Laravel 6 – 12
- PHP >= 8.1

**Changes from the original:**
- Added Laravel 11 and 12 support (illuminate/* `^11.0|^12.0`)
- Fixed PHP 8.3 deprecation: replaced `strftime()` with `IntlDateFormatter` in `selectMonth()`
- Fixed PHP 8.0+ deprecation: optional parameter before required in `HtmlBuilder::__construct()`
- Improved `FormAccessible` trait: enum cast support, null-safe relation handling, modern date detection

**Installation via VCS repository:**
```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/protrainup/laravel-collective-html"
        }
    ],
    "require": {
        "laravelcollective/html": "dev-main"
    }
}
```
