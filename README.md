# Breeze Blank

This is a metapackage for [swissup/theme-frontend-breeze-blank](https://github.com/breezefront/theme-frontend-breeze-blank).

> Metapackage — is more complete bundle that may include additional non-mandatory
> dependencies.

 - [Docs](https://breezefront.com/about)
 - [Demo](https://breeze.swissupdemo.com/breeze_blank/)
 - [Screenshots](https://breezefront.com/screenshots#breeze-blank)

## Installation

```bash
composer require swissup/breeze-blank
bin/magento setup:upgrade --safe-mode=1
```

## Configuration

Activate theme using _Content > Design > Configuration_ page or install
our `swissup/module-marketplace` module and run one-click installer:

```bash
composer require swissup/module-marketplace
bin/magento setup:upgrade --safe-mode=1
bin/magento marketplace:package:install swissup/breeze-blank
```
