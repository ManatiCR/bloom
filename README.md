# Bloom Install Profile [![Build Status](https://travis-ci.org/ManatiCR/bloom.svg?branch=8.x)](https://travis-ci.org/ManatiCR/bloom)

A base Drupal install profile to scaffold Manatí projects.

## How to use it?

On any Drupal project, add bloom to your composer dependecies:

```php
composer require manaticr/bloom
```

Install the site using `bloom` profile.

```bash
drush si bloom --account-pass=admin --site-name="Drupal8" -y
```

Enjoy your site!!
