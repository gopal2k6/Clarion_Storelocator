Clarion Storelocator
=================================

For more information visit http://www.magentocommerce.com/magento-connect/store-locator-with-google-map-1.html

*Please note that we are not the developer of this extension. In this repo we only added modman/composer support. We will not provide any support for this repository. If you have problems on integration, please use the official link mentioned above.*


Installation
------------

1. Add `require` and `repositories` sections to your composer.json as shown in example below and run `composer update`.
2. Configure options in in System -> Configuration -> Kirchbergerknorr -> TrustedBadge. 
3. Actiavate logs and module.

*composer.json example*

```
{
    ...
    
    "repositories": [
        {"type": "git", "url": "https://github.com/kirchbergerknorr/Clarion_Storelocator"},
    ],
    
    "require": {
        "kirchbergerknorr/Clarion_Storelocator": "*"
    },
    
    ...
}
```

