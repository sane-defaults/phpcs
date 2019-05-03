# Sane defaults for [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors)

## Instructions for use

```bash
composer require --dev friendsofphp/php-cs-fixer
curl https://raw.githubusercontent.com/sane-defaults/phpcs/master/.php_cs > .php_cs
```

Don't forget to adjust excluded paths by adding `$finder->exclude()` in `.php_cs`.

In order to run it just run `phpcs` or check out our [grumphp](https://github.com/sane-defaults/grumphp) integration.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/all-contributors/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="https://www.sourceguru.net"><img src="https://avatars3.githubusercontent.com/u/570639?v=4" width="100px;" alt="Martin Meredith"/><br /><sub><b>Martin Meredith</b></sub></a><br /><a href="https://github.com/sane-defaults/phpcs/commits?author=mezzle" title="Code">💻</a> <a href="#ideas-mezzle" title="Ideas, Planning, & Feedback">🤔</a> <a href="#review-mezzle" title="Reviewed Pull Requests">👀</a></td><td align="center"><a href="https://github.com/mrliptontea"><img src="https://avatars1.githubusercontent.com/u/3495587?v=4" width="100px;" alt="Grzegorz Rajchman"/><br /><sub><b>Grzegorz Rajchman</b></sub></a><br /><a href="https://github.com/sane-defaults/phpcs/commits?author=mrliptontea" title="Code">💻</a> <a href="#ideas-mrliptontea" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/sane-defaults/phpcs/commits?author=mrliptontea" title="Documentation">📖</a> <a href="#review-mrliptontea" title="Reviewed Pull Requests">👀</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!