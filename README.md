# Magento 2 Clearance Products Page and Widget ##

Frontend controller to display clearance products with layered navigation.

For products to display they must be on set as clearance yes under the selected store scope.  Plus any additional rules that would apply to a product collection on your store such as visibility or stock.

The widget needs to be configured from the admin

# Install instructions #

`composer require dominicwatts/clearance`

`php bin/magento setup:upgrade`

`php bin/magento setup:di:compile`

# Usage instructions #

Set clearance attribute to yes on products

Go to `/clearance`

Configure widget in backend