# Payu_Magento_v2.x_Kit

Supported Versions
Payu Plugin version V1.0 Magento supported version 2.1

Installation and Configuration
upload app/code/PayUIndia (all files and folder) at you server end.

Run below command:
php bin/magento module:enable PayUIndia_Payu
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy

goto Admin->Store->Configuration->Sales->Payment Method->Payu
fill details here and save them.

goto Admin->System->Cache Management
Clear all Cache.

Now you can collect payment via Payu.

In case of any issue Kindly write us at tech@payu.in