### Magento Config Admin Values
Little extension which adds Admin website scope in storeswitcher in system config section.

This extension adds Admin website scope, as shown on screenshot:

![](http://www.creativecast.de/ak/2015-07-30_093939.png)

### Background

When using cloudfront, by default backend image uploader and media gallery didn't work (cross-domain security issue). 
Solution for this is to set skin and js paths local for backend section (and keeping CDN path for frontend), with this extension it's much easier than having to edit core_config_data manually.
