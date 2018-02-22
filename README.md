                                           _
		______   ____    _________| |   _______	   _______      _______	   ______
		|   _ \_/_   | 	|           |  |   __  \   |   ____|  /   ____|   /  __  \
		|  | |  | |  | 	|           |  |  |  |  |  |       |  |       |  |  |  |
		|  | |  | |  | 	| /\	/ \ |  |  |__|  |  |  |____   |  |____   |  |__|  |
		|  | |  | |  | 	|/  \  /   \|  |   ____/   |   ____|  |____   |  |   __   |
		|  | |  | |  | 	|\   \/	   /|  |  |        |  |            |  |  |  |  |  |
		|  | |  | |  | 	| \	  / |  |  |        |  |____    ____|  |  |  |  |  |
		|__| |__| |__|	|  \____/   |  |__|        |_______|  |_______/  |__|  |__|
				|	    |
				|           |
				|___________|
						
# MPESA For WooCommerce
WordPress Plugin that extends WordPress and WooCommerce functionality to integrate MPESA for making payments, remittances, checking account balance transaction status and reversals. It also adds Kenyan Counties to the WooCommerce states list.
![alt text](https://user-images.githubusercontent.com/14233942/31839718-fefe17ca-b5ea-11e7-9afa-95fa395a8e43.png)

This plugin depends on and makes extensive use of ![this M-Pesa library](https://github.com/ModoPesa/mpesa-php).

## Installation
Getting started with MPESA for WooCommerce is very easy. All configuration is done in the WooCommerce settings in the WordPress admin dashboard.

### Requirements
Your site/app MUST be running over https for the MPESA Instant Payment Notification (IPN) to work.

### Auto-installation
* In your WordPress admin, navigate to Plugins and search for MPESA for WooCommerce.
* Click the install button and the plugin will be installed. Once installed, activate the plugin and configure it at http://yoursite.com/wp-admin/admin.php?page=wc-settings&tab=checkout&section=mpesa

### Manual Installation 
* First, you need to download the latest release of the plugin from [the WordPress plugin repository](https://plugins.wordpress.org/wc-mpesa).
* Using an FTP program, or your hosting control panel, upload the plugin folder (wc-mpesa) to your WordPress installation’s wp-content/plugins/ directory.
* Activate the plugin from the Plugins menu within the WordPress admin

That is all. You are now ready to receive and send money using MPESA on your WordPress and WooCommerce powered site.

## Contributing
* Fork the repo, do your magic and make a pull request.

## Pro Version
While this plugin provides adequate MPESA integration for a basic ecommerce site/app, we also offer a pro version for those who want more.

### Features
* Advanced C2B/B2B/B2C/Status APIs 
* Analytics
* 24/7 Support
* Branding Customizations
* PDF Export/Print

### Cost
* KSH 599/yr
* $6/yr

## Acknowledgements
* MPESA and the MPESA Logo are registered trademarks of Safaricom Ltd
* WordPress and the WordPress logo are registered trademarks of Automattic Inc.
* WooCommerce and the WooCommerce logo are registered trademarks of Automattic Inc.
