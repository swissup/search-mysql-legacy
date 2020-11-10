# Search Mysql Legacy
Magento2 module for FAQ

<sup>It's a metapackage for the [original repository](https://github.com/swissup/module-search-mysql-legacy).</sup>

### Installation

Run the following commands:
```bash
cd <magento_root>
composer config repositories.swissup composer https://docs.swissuplabs.com/packages/
composer require swissup/search-mysql-legacy --prefer-source --ignore-platform-reqs
bin/magento module:enable Swissup_Core Swissup_SearchMysqlLegacy
bin/magento setup:upgrade
bin/magento setup:di:compile
```
