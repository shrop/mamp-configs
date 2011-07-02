### My MAMP configuration files with SSL enabled
* Built with MAMP 1.9.6 (http://www.mamp.info/en/index.html)
* To setup:
 * Remove folder /Applications/MAMP/conf
 * Clone this repo to /Applications/MAMP/conf
* The ssl folder contains a generic ssl key and crt for the cn: default.site. Ignore the ssl errors and it will work fine for testing sites with SSL.
* This setup is configured to use VirtualHostX (http://clickontyler.com/virtualhostx/) to setup Apache vhosts. Virtual hosts can be manually edited directly at /private/etc/apache2/extra/httpd-vhosts.conf.
