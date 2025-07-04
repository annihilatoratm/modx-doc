# PaynetEasy Payment Plugin for Modx 2.8.7

# 1. [Requirements](https://github.com/annihilatoratm/modx-doc/blob/main/documentation/modx-eng.md#1-requirements-1) 
# 2. [Plugin Installation](https://github.com/annihilatoratm/modx-doc/blob/main/documentation/modx-eng.md#2-plugin-installation-1)
# 3. [Plugin Uninstallation](https://github.com/annihilatoratm/modx-doc/blob/main/documentation/modx-eng.md#3-plugin-uninstallation-1)

## 1. Requirements

* PHP version: 7.4 or more (tested on version 8.1).  
* Modx version: 2.8.7 (or any < 3.0).  
* Plugin Minishop2.  

## 2. Plugin Installation  

2.1. Connect via FTP to the server and place the folder “mspPaynetEasy” with the plugin in the root folder of the site. For package information go to the [web-site](https://website.com/mspPaynetEasy/_build/build.transport.php) and start plugin installation.  
2.2. Navigate to Settings:  
   * Packages -> miniShop2 -> Settings.  
2.3. Go to the _Payment Methods_ tab.  
2.4. For the created _PaynetEasy Payment_ payment method select the action _Change_.  
2.5. Go to the _Delivery options_ tab and enable the available options for this payment system.  
2.6. Navigate to System Settings:  
   * Packages -> miniShop2 -> System Settings.  
2.7. In the key search field, specify **paynet** and press **Enter**.  
2.8. In the _Value_ column, click twice on the desired parameter and open the input field. Fill in all plugin settings.  
2.9. Redirection configuration:  
   * After checkout, enter page id for _Successful payment page_ and for _Unsuccessful payment page_.  
2.10. If the payment method does not appear in the cart, check if the _payment method_ is enabled on the settings page.  

## 3. Plugin Uninstallation

3.1. Navigate to Settings:  
   * Packages -> miniShop2 -> Settings.  
3.2. Find _PaynetEasy_ and select the **Delete** action.  
3.3. Go to the server and delete the folder _mspPaynetEasy_ from the root folder of the site:  
   * Delete the file on the server “payneteasy.class.php” at site_folder/core/components/minishop2/custom/payment/  
   * Delete the file on the “payneteasy.php” server at the address site_folder/assets/components/minishop2/payment/  
   * Delete the file on the server “payneteasy-setting-fields.combo.js” at site_folder/assets/components/csf/js/mgr  
   * Delete the file on the server “msp.payneteasy.inc.php” at site_folder/core/components/minishop2/lexicon/en  
   * Delete the file on the server “msp.payneteasy.inc.php” at site_folder/core/components/minishop2/lexicon/ru
   * Delete the file on the server «msppayneteasy-1.0.0-pl.transport.zip» at site_folder/core/packages
   * Delete the file on the server «msppayneteasy-1.0.0-pl» at site_folde/core/packages









