# Statamic Widget: Cache Controller

Fork of [webographen/statamic-widget-cache-controller](https://github.com/webographen/statamic-widget-cache-controller) with Statamic 6 support.

Lets you clear all of Statamic's caches from the control panel dashboard.

## Requirements

- Statamic v6

## Installation

Add the VCS repository and require the package in your `composer.json`:

```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/celticostravel/statamic-widget-cache-controller"
    }
],
"require": {
    "celticostravel/statamic-widget-cache-controller": "^1.1"
}
```

Then run `composer update`.

## Usage

Add the widget to your dashboard in `config/statamic/cp.php`:

```php
[
    'type' => 'cache_controller',
    'width' => 50,
],
```
