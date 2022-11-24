# iTop extension: set-portal-default-to-mosaic
* [Description](#description)
* [Compatibility](#compatibility)
* [Installation](#installation)
* [Configuration](#configuration)
* [Licensing](#licensing)

## Description
This extension sets the *mosaic* view mode of the service catalog for the user portal in iTOP.

Inspirated by [Molkobain's extension](https://github.com/Molkobain/itop-portal-mosaic-service-catalog)


## Compatibility
Compatible with iTop 3.0.0+

## Installation
* Unzip the extension
* Copy the files to``set-portal-default-to-mosaic`` folder under ``<PATH_TO_ITOP>/extensions`` folder of your iTop
* Run iTop setup & select extension *Set Mosaic as the default browse mode*

## Configuration
### Standard portal
No configuration needed.

### Customized portal
If you customized the user portal, you will have to check/modify 2 things on the ``datamodel.set-portal-default-to-mosaic.xml`` file of the extension, then run an iTop setup.
* Portal ID: If your portal ID is not ``itop-portal``, change it to your custom ID on line 4.
* Service catalog brick: If you are not targetting the standard service catalog, change the brick ID on line 6 (``services``) with yours.

## Licensing
This extension is under GNU General Public License v3.0
