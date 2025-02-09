scheb/two-factor-bundle
=======================

### ⚠ Outdated version - EOL in November 2021. Please use versions ≥ 5 from [scheb/2fa](https://github.com/scheb/2fa).

---

This bundle provides **[two-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication) for your
[Symfony](https://symfony.com/) application**.

[![Build Status](https://github.com/scheb/two-factor-bundle/workflows/CI/badge.svg?branch=4.x)](https://github.com/scheb/two-factor-bundle/actions?query=workflow%3ACI+branch%3A4.x)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/scheb/two-factor-bundle/badges/quality-score.png?b=4.x)](https://scrutinizer-ci.com/g/scheb/two-factor-bundle/?branch=4.x)
[![Code Coverage](https://scrutinizer-ci.com/g/scheb/two-factor-bundle/badges/coverage.png?b=4.x)](https://scrutinizer-ci.com/g/scheb/two-factor-bundle/?branch=4.x)
[![Latest Stable Version](https://img.shields.io/packagist/v/scheb/two-factor-bundle)](https://packagist.org/packages/scheb/two-factor-bundle)
[![Monthly Downloads](https://img.shields.io/packagist/dm/scheb/two-factor-bundle)](https://packagist.org/packages/scheb/two-factor-bundle/stats)
[![Total Downloads](https://img.shields.io/packagist/dt/scheb/two-factor-bundle)](https://packagist.org/packages/scheb/two-factor-bundle/stats)
[![License](https://poser.pugx.org/scheb/two-factor-bundle/license.svg)](https://packagist.org/packages/scheb/two-factor-bundle)

<p align="center"><img alt="Logo" src="Resources/doc/2fa-logo.svg" /></p>

---

It comes with the following two-factor authentication methods:

- [TOTP authentication](https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm)
- [Google Authenticator](https://en.wikipedia.org/wiki/Google_Authenticator)
- Authentication code via email

Additional features you will like:

- Interface for custom two-factor authentication methods
- Trusted IPs
- Trusted devices (once passed, no more two-factor authentication on that device)
- Single-use backup codes for when you don't have access to the second factor device
- Multi-factor authentication (more than 2 steps)
- CSRF protection
- Whitelisted routes (accessible during two-factor authentication)

Installation
-------------

```bash
composer require scheb/two-factor-bundle
```

... and follow the [installation instructions](Resources/doc/installation.md).

Documentation
-------------
Detailed documentation of all features can be found in the [Resources/doc](Resources/doc/index.md) directory.

Version Guidance
----------------

If you have Symfony ≥ 4.4 and start using the bundle, please use bundle version 5, which is available as
`scheb/2fa-bundle` from the [scheb/2fa](https://github.com/scheb/2fa) repository.

| Version        | Status                        | Symfony Version  |
|----------------|-------------------------------|------------------|
| [1.x][v1-repo] | EOL                           | >= 2.1, < 2.7    |
| [2.x][v2-repo] | EOL                           | ^2.6, ^3.0, ^4.0 |
| [3.x][v3-repo] | EOL                           | 3.4, ^4.0, ^5.0  |
| [4.x][v4-repo] | Security fixes until Nov 2021 | 3.4, ^4.0, ^5.0  |
| [5.x][v5-repo] | New features + Bug fixes      | 4.4, ^5.0        |

[v1-repo]: https://github.com/scheb/two-factor-bundle/tree/1.x
[v2-repo]: https://github.com/scheb/two-factor-bundle/tree/2.x
[v3-repo]: https://github.com/scheb/two-factor-bundle/tree/3.x
[v4-repo]: https://github.com/scheb/two-factor-bundle/tree/4.x
[v5-repo]: https://github.com/scheb/2fa/tree/5.x

License
-------
This bundle is available under the [MIT license](LICENSE).

Security
--------
For information about the security policy and know security issues, see [SECURITY.md](SECURITY.md).

Contributing
------------
Want to contribute to this project? See [CONTRIBUTING.md](CONTRIBUTING.md).

Support Me
----------
I'm developing this library since 2014. I love to hear from people using it, giving me the motivation to keep working
on my open source projects.

If you want to let me know you're finding it useful, please consider giving it a star ⭐ on GitHub.

If you love my work and want to say thank you, you can help me out for a beer 🍻️
[via PayPal](https://paypal.me/ChristianScheb).
