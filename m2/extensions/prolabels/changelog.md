---
layout: default
title: Prolabels Changelog
description: Prolabels changelog
keywords: prolabels changelog
category: Prolabels
---

# Changelog

### Version 1.4.1

> Dec 6, 2019

 -  Improve stability at frontend. Prevent division by zero. Occurs when product special price is 0.0000.

### Version 1.4.0

> Nov 19, 2019

 -  Added advanced text editor for product labels text and CSS in Magento Admin. Check how updated interface [here](/m2/extensions/prolabels/interfaces/#product-label-tab-and-category-label-tab). Advanced text editor based on CodeMirror library.
 -  Fixed missing onSale label for grouped products.

### Version 1.3.7

> Oct 16, 2019

 -  Remove direct 'jquery/ui' usage to improve js performance.

### Version 1.3.6

> Aug 21, 2019

 -  New label added: "Argento Force rectangle label with offset"

### Version 1.3.4

> Jul 16, 2019

 -  Fixed missing category labels on Magento 2.3.x (after fixed missing special price at listings in Magento 2.2.x in previous release).


### Version 1.3.3

> Jul 15, 2019

 -  Fixed missing special price at product listing when ProLabels module enabled.

### Version 1.3.2

> Jun 12, 2019

 -  Use JSON to store labels conditions instead of serialize.
 -  Show labels in recently viewed products widget.
 -  Fixed lables index update when save configurable product.

### Version 1.3.1

> May 15, 2019

 -  Fixed incorrect prices in labels when tax included in price. Respect tax settings.
 -  Improve OnSale label determination for configurable products.

### Version 1.3.0

> Apr 11, 2019

 -  Improve module styles. Merge module CSS with theme CSS.

### Version 1.2.7

> Mar 29, 2019

 -  Magento 2.3 compatibility (Fixed broken file uploader)

### Version 1.2.6

> Jan 15th, 2019

 -  8 new prolable presets with Font Awesome icons. Search for "hexagon" in presets. You may need [Font Awesome module](https://github.com/swissup/module-font-awesome) to get full advantage of new presets.

    ![New labels](/images/m2/prolabels/changelog/version-1_2_6.png)

 -  Small source code improvements and optimizations.

### Version 1.2.5

> Jan 4th, 2019

 -  Fix issues with caching of In Stock label.

### Version 1.2.4

> Jan 2nd, 2019

 -  Current version allows to use predefined variables in style attribute of tags in label text.
 -  Requires Swissup Core module version 1.8+ to reuse FileInfo model in admin interfaces.

### Version 1.2.3

> Dec 11th, 2018

 -  Fix error during labels appling at some Magento Commerce (Enterprise) stores.
 -  Better logic to determine whether "On sale" label can be shown.
 -  Few JavaScript and CSS fixes to make module more stable.
 -  Improve manual labels appling (me simple products were missed from indexes if they were children of configurable product).

### Version 1.2.0

> Oct 10th, 2018

Internal module naming convention was updated. We applied this changes to reach full compatibility with Magento Marketplace policy.

### Version 1.1.0

> Sep 21st, 2018

> You may get errors during DI compilation when upgrdaing from previous version. So check [upgrade instruction](../installation/manual/#upgrade-from-version-10x-to-110).

It's not a regular update. It's a fresh start for Prolabels module on Magento 2!

 -  Instant preview in Magento Admin.
 -  15 label presets. Now you can create product label in 3-5 mouse clicks.
 -  No need to modify templates to get labels on category page in any Magento theme. Even more. You get labels in third-party widgets (as long as they developed with Magento recommendations).
 -  Significant code improvement to meet Magento standards and follow best practices.

### Version 1.0.23

 -  Fixed compatibility with Argento product listing styles

### Version 1.0.22

 -  Optimize labels rendering on storefront.
 -  Fixed invalid discount values calculation for non-base currencies.
 -  Fixed warning illegal offset during CLI reindex.

### Version 1.0.19

 -  Code cleanup and stability improvements

### Version 1.0.18

 -  Magento 2.2 compatibility

### Version 1.0.17

 -  Fix missing labels after cron run at some Magento instances.
 -  ACL improvements according latest Magento requirements.
