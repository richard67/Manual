---
sidebar_position: 2
---

New deprecations
===============
All the new deprecations that should be aware of and what you should now be using instead.
:::caution TODO

This page is unfinished, please use the **Edit this Page** link at the bottom of this page to help make it more useful.

:::


#### The item_associations property of the WebApplication class is deprecated

File: libraries/src/Application/WebApplication.php
Replacement: The $item_associations property will be removed with no replacement as it is not used in core anymore.

#### Privacy plugin app property is deprecated

File: administrator/components/com_privacy/src/Plugin/PrivacyPlugin.php
Replacement: The `$this->app` property is deprecated in the privacy plugins. Instead of use `$this->getApplication()` when the plugin is converted to service providers.
