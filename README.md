# ACF Country field

Adds a 'Country' field type for the [Advanced Custom Fields](http://wordpress.org/extend/plugins/advanced-custom-fields/) WordPress plugin.

-----------------------

### Overview

Display a select list of all countries in your language.

Country names are available in every language ([see available list](https://github.com/umpirsky/country-list/tree/master/data)). By default, country names are localized in your current WordPress language.

Select a single value:

![ACF Country field](https://dl.dropboxusercontent.com/u/54390968/dev/acf-country_single.png)

Or multiple ones:

![ACF Country field](https://dl.dropboxusercontent.com/u/54390968/dev/acf-country_multiple.png)

### Compatibility

This add-on will work with:

* ACF version 4
* ACF version 5 (pro)
* PHP 5.3 or higher

### Field options

* Allow null: enable/disable null value (disabled by default)
* Allow multiple: enable/disable multiple countries selection (disabled by default)
* Stylised UI: enable/disable enhanced select field thanks to [Select2](https://select2.github.io/) (enabled by default)
* Return format:
	* country code and country name (default):
		* single: `array('FR' => 'France')`
		* multiple: `array('FR' => 'France', 'DE' => 'Allemagne')`
	* country code:
		* single: `FR`
		* multiple: `array('FR', 'DE', 'ES')`
	* country name:
		* single: `France`
		* multiple: `array('France', 'Allemagne', 'Espagne')`

### Installation

#### WordPress admin

In plugins/add section, search for "acf country" and click "install".

#### Zip

[Download](https://github.com/nlemoine/acf-country/archive/master.zip) the plugin and extract the plugin to your plugins folder.

#### Composer

```bash
composer require hellonico/acf-country
```
