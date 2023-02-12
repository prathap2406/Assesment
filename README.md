Steps to enable :

1. Place this module/extension under app/code
2. Run this cmd in magento root : bin/magento module:enable Valtech_Assesment
3. Run these cmd in magento root,
	- bin/magento setup:upgrade
	- bin/magento set:static-content:deploy : This is required for the js to be deployed in pub/static
	- bin/magento cache:flush :  This is flush all the cache
