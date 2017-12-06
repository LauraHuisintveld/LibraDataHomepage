# Branding UVa Dataverse

In Dataverse 4.7.1, customizations/brandings was made possible.

You can add a custom welcome/homepage as well as other custom content, to further brand your installation and make it your own. Here are the custom branding and content options you can add:

* Custom welcome/homepage
* Logo image to navbar
* Header
* Footer
* CSS stylesheet

Files used for UVa homepage configuration are included in this github repo.

One has to log on to the local dataverse server and put the configuration files in these folders:
html pages (homepage, footer, header, CSS stylesheet) are located here: /var/www/dataverse/branding
Custom logo goes here: /usr/local/glassfish4/glassfish/domains/domain1/docroot/logos/navbar

## More Information
On Dataverse Configuration Guide: http://guides.dataverse.org/en/4.8.3/installation/config.html?highlight=homepage
