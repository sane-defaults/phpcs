# Sane defaults for [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

## Instructions for use

```bash
composer require --dev friendsofphp/php-cs-fixer
curl https://raw.githubusercontent.com/sane-defaults/phpcs/master/.php_cs > .php_cs
```

Don't forget to adjust excluded paths by adding `$finder->exclude()` in `.php_cs`.

In order to run it just run `phpcs` or check out our [grumphp](https://github.com/sane-defaults/grumphp) integration.
