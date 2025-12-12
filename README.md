# Unzer PAPI Payments — Hyvä Themes Compatibility

A Hyvä Themes compatibility module for **Unzer PAPI Payments**.

This module integrates **Unzer Payments** with **Hyvä Checkout**, providing seamless compatibility with Hyvä storefronts.

## Requirements

- Magento 2.4.6, 2.4.7 or 2.4.8
- [Base Unzer Magento 2 Plugin](https://docs.unzer.com/plugins/magento-2/) installed.
- [Hyvä Theme module](https://docs.hyva.io/hyva-themes/getting-started/index.html) installed.

## Installation

### Install the Plugin using Composer
```bash
composer require unzerdev/magento2-hyva-compatibility
```
### Once Composer has installed the dependencies and the plugin, activate it:

```bash
php bin/magento module:enable Unzer_HyvaCompatibility --clear-static-content
```
### Import the plugin schema into your database:

```bash
php bin/magento setup:upgrade
```

### Clear the cache, generate dependency injection, and deploy static files:
```bash
php bin/magento cache:flush
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```

## Support

For any issues or questions please get in touch with our support.

**Email**: support@unzer.com

**Phone**: +49 (0)6221/6471-100

**Twitter**: [@UnzerTech](https://twitter.com/UnzerTech)

**Webpage**: https://unzer.com/
