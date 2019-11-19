# glynn theme bundle

[![Check on packagist][packagist-badge]][packagist]
[![MIT License][license-badge]][LICENSE]

[![Watch on GitHub][github-watch-badge]][github-watch]
[![Star on GitHub][github-star-badge]][github-star]
[![Tweet][twitter-badge]][twitter]

### Instalation

```
composer req disjfa/glynn-theme-bundle
```

### About

Basic theme bundle. Can be used in [glynn-admin-symfony4](https://github.com/disjfa/glynn-admin-symfony4). You can use the templates by extending the templates in your application. For the admin interface it uses the base of [glynn-admin](https://disjfa.github.io/glynn-admin/).

### How!

How, just extend some files in your main `templates` folder:

```twig
{% extends "@GlynnTemplate/admin.html.twig" %}
```

### Enjoy!

Make awesome stuff!

[packagist-badge]: https://img.shields.io/packagist/v/disjfa/glynn-theme-bundle
[packagist]: https://packagist.org/packages/disjfa/glynn-theme-bundle
[license]: https://github.com/disjfa/glynn-theme-bundle/blob/master/LICENSE
[license-badge]: https://img.shields.io/github/license/disjfa/glynn-theme-bundle.svg
[github-watch-badge]: https://img.shields.io/github/watchers/disjfa/glynn-theme-bundle.svg?style=social
[github-watch]: https://github.com/disjfa/glynn-theme-bundle/watchers
[github-star-badge]: https://img.shields.io/github/stars/disjfa/glynn-theme-bundle.svg?style=social
[github-star]: https://github.com/disjfa/glynn-theme-bundle/stargazers
[twitter-badge]: https://img.shields.io/twitter/url/https/github.com/disjfa/glynn-theme-bundle.svg?style=social
[twitter]: https://twitter.com/intent/tweet?text=Check%20out%20glynn-theme-bundle!%20-%20Cool%symfony%20templates!%20Thanks%20@disjfa%20https://github.com/disjfa/glynn-theme-bundle%20%F0%9F%A4%97
