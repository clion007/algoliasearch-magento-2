Algolia Search for Magento 2
==================

![Latest version](https://img.shields.io/badge/latest-2.0.0-green.svg)
![Magento 2](https://img.shields.io/badge/Magento-%3E=2.2-blue.svg)
![PHP >= 7.0.6](https://img.shields.io/badge/PHP-%3E=7.0-green.svg)

[![CircleCI](https://circleci.com/gh/algolia/algoliasearch-magento-2/tree/master.svg?style=svg)](https://circleci.com/gh/algolia/algoliasearch-magento-2/tree/master)

-------

🔎 Are you a Magento engineer? [Join our team](https://www.algolia.com/careers#!?j=eed58660-f684-436d-a2ff-e9947d2b65a2) and help us deliver the best search solution for Magento stores!

-------

- **Auto-completion menu:** Offer End-Users immediate access to your whole catalog from the dropdown menu, whatever your number of categories or attributes.

- **Instant search results page:** Have your search results page, navigation and pagination updated in realtime, after each keystroke.

Official website: [community.algolia.com/magento](https://community.algolia.com/magento).

*Note: if your store is running under Magento version 1.x, please check our [Algolia for Magento 1 extension](https://github.com/algolia/algoliasearch-magento).*

Demo
--------------

Try the auto-complete and the instant search results page on our [live demo](https://magento2.algolia.com). 

Algolia Search
--------------

[Algolia](http://www.algolia.com) is a search engine API as a service capable of delivering realtime results from the first keystroke.

This extension replaces the default search of Magento with a typo-tolerant, fast & relevant search experience backed by Algolia. It's based on [algoliasearch-client-php](https://github.com/algolia/algoliasearch-client-php), [autocomplete.js](https://github.com/algolia/autocomplete.js) and [instantsearch.js](https://github.com/algolia/instantsearch.js).

<!-- 
The extension officially supports only 2.0.X versions of Magento. 
It's possible to use it for versions >= 2.1.0, but some unexpected issues might appear. When you experience that, please [open an issue](https://github.com/algolia/algoliasearch-magento-2/issues/new).
-->

Documentation
--------------

Check out the [Algolia Search for Magento 2 documentation](https://www.algolia.com/doc/integration/magento-2/getting-started/quick-start/).


Installation
------------

The easiest way to install the extension is to use [Composer](https://getcomposer.org/) and follow our [getting started guide](https://www.algolia.com/doc/integration/magento-2/getting-started/quick-start/).

Run the following commands:

- ```$ composer require algolia/algoliasearch-magento-2```
- ```$ bin/magento module:enable Algolia_AlgoliaSearch```
- ```$ bin/magento setup:upgrade && bin/magento setup:static-content:deploy```

Upgrading from 1.x to 2.x
------------
With the release of a new major version, we have decided to create minor and major version releases to allow those that want to continue on the minor version. This update will **break compatibility**. Please read the [upgrade guide](https://www.algolia.com/doc/integration/magento-2/getting-started/upgrading/#upgrading-from-v1-to-v2) for all of the file changes and updates included in this release. 

If you would like to stay on the minor version, please upgrade your composer to only accept versions less than version 2 like the example:

`"algolia/algoliasearch-magento-2": ">=1.13.1 <2.0"`

Contribution
------------

To start contribuiting to the extension follow the [contributing guildelines](.github/CONTRIBUTING.md).
