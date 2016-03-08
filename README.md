#Stock Checker Script
## Host Your Own Affiliate Stock Checker

Start your own Stock Checker with this script, you'll be able to scan any product website for specific keywords to see whether the product is in or out of stock. Users can choose to receive email, twitter or on-site sound alerts when a product becomes available for many different retailers websites. Easy to setup/install and use, built upon Twitter Bootstrap.

## Features

1. Stock Checking
2. Stock History
3. Email Alerts
4. Twitter Alerts
5. Onsite/Sound Alerts

### Admin Features

1. Add Merchants/Retailers
2. Add Categories
3. Add Products with Affiliate Links

### User Features

1. Register a Free Account
2. Receive Email Alerts for Chosen Products
3. Receive Twitter Alerts for Chosen Products
4. Receive On-Site Sound Alerts for Chosen Products

## Installation

1. Import stock.sql into your databse.
2. Setup your settings in config.php, most important are under "Database Definitions", "SMTP (Mail) Settings" and "Twitter Settings" sections.
3. If you use different mysql tables, you must edit "Database Tables" section in same config too.
4. DO NOT DELETE admin's user. You can change the password, but do not delete it, as it's the only one with all permissions. If you want to allow other user to be admin, it should be added to current system or you can do it manually in the db (table: ss_users, column: user_role).
5. Make sure following folders are writable from the web (777):<br />
>assets/upload/<br />
>tmp/<br />
>tmp/sesstmp/<br />
>tmp/sesstmp/<br />
>templates_c/
6. Setup cronjob in Cpanel so the script checks whether the products are in or out of stock automatically.

## Usage

1. Once installed go to /admin/
2. Add retailers and their logos
3. Add categoires for products you're going to stock check
4. Add URLs for the products you have setup to stock check

## Demo

You can view the demo of this script in use <a href="http://stockchecker.dyversedigital.com/demo/">here</a>. You can also login as admin and test out using the script by adding retailers, products and links.

####Admin Login Details

**Username:** Admin<br />
**Password:** Admin

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Version History

Stock Checker uses the <a href="http://semver.org">SemVer</a> versioning (major.minor.patch).<br />
Latest Version: **v1.0.0**

## Support

Please open an issue or sumbit a ticket at <a href="http://support.dyversedigital.com/stockchecker">support.dyversedigital.com/stockchecker/</a>

## Credits

**Nathan Ayling**<br />
**Twitter:** <a href="http://twitter.com/NathanAyling">@NathanAyling</a><br>
**Website:** <a href="http://nathanayling.com">nathanayling.com</a><br>

**Dyverse Digital**<br />
**Twitter:** <a href="http://twitter.com/dyversedigital">@DyverseDigital</a><br />
**Website:** <a href="http://dyversedigital.com">dyversedigital.com</a>
